# GNN_Ricci

## Ricci-filled

The Forman-Ricci values are filled by using this formula for every edges in the graph:

$w*e\*(\frac{w*{v*1}}{w_e} - \sum*{e*{I, v_1} \sim e}{\frac{w*{v*1}}{\sqrt{w_e\*w*{e*I, v_1}}}}) $ + $w_e\*(\frac{w*{v*2}}{w_e} - \sum*{e*{O, v_2} \sim e}{\frac{w*{v*2}}{\sqrt{w_e\*w*{e_O, v_2}}}}) $

- Using this formula for every edges in the graph make some edges that are bidirectional having two value - 1 value for in-edge and another for out-edge

![filled graph](Forman_Ricci.png)
