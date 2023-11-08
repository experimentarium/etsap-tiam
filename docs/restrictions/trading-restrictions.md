# Global Trade of Commodities

### Implementation
In TIAM, there is the possibility of trading commodities along the different regions of the TIAM. This can be done either through bidirectional trading or unidirectional trading. For implementation, a trading matrix is used where the traded commodity must be specified as well as the participating trading regions, see figure 1 and figure 2.

Figure 1: Bidirectional trade of commodities between region 1 (REG1) and region 2 (REG2).
![Bidirectional trade](./figs/bi_trade.png) 

Figure 2: Unidirectional trade of commodities between region 1 (REG1) and region 2 (REG2). 
![Unidirectional trade](./figs/un_trade.png)

The trade matrix only established the links between trading regions but not the cost that occur when trading. This can separately be applied by using user constrains to the trades. This could either be done via invest cost (e.g. for pipeline transport) or via activity cost (e.g. for shipping transport). 
Furthermore, the activity of trade could be limit via user constrains as well. 

### Trades in TIAM

Trades are implemented in TIAM for commodities as crude oil, coal, natural gas naphtha, gasoline, LNG and uranium. All of the trades are calibrated based on the IEA energy statistics of 2015.
