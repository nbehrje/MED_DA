# MED_DA: Monotonicity Entailment Dataset — Determiner Arguments

This is a dataset that covers monotonicity reasoning.
It is based on [MED](https://github.com/verypluming/MED) by Hitomi Yanaka, Koji Mineshima, Daisuke Bekki, Kentaro Inui, Satoshi Sekine, Lasha Abzianidze, and Johan Bos.
A few corrections have been made to entries from MED, and 544 additional entries were added.
Where applicable, an additional annotation was added to the `genre` field indicating whether the left (first) or right (second) argument of the determiner was the one that changed between the first and second sentence.
The purpose of these modifications is to better understand how well models can learn the monotonicity of determiners and to increase the balance among up+left/up+right/down+left/down+right examples.
