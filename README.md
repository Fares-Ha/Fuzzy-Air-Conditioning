# Fuzzy-Air-Conditioning

I have proposed a plan to maintain a temperature and humidity level close to the targeted values while reducing the electrical energy consumption of the compressor/fan unit by utilizing all available resources in the most efficient way.

The input parameters include user temperature (Ut), temperature difference (Tdiff), and dew point (Td).

The output parameters include compressor speed (Sc) and fan speed (Sf), operating mode (Mo), and fan direction (Fn).

Ut contains three fuzzy sets, Tdiff has four fuzzy sets, and Td has two fuzzy sets, resulting in a 3x4x2=24 cell matrix. Each cell contains four outputs, namely compressor speed, fan speed, operating mode, and fan direction.

This is equivalent to a total of 24 IF-THEN rules.

