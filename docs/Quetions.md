1) Open item (not yet asked/confirmed): this doc assumes basic auth is required for MVP, the same way it was required for the other two capstones with persistent user data. Flag if Pavan intends positions to be session-only / unauthenticated for MVP instead
2) what is the plan for UI can no we need to build ui From scrach or use trding view plugin
3) Do we need all the indicators for mvp : User can toggle on any of the following for that chart — confirmed as 10, not the original draft's "one or two," a real scope increase worth flagging explicitly:
4) How to communicate buy and sell signal to the user(mode of communication through message or on chart display): These are chart overlays for visual analysis — they do not by themselves generate a buy/sell signal. Only §4.4's strategy does that for MVP
5) For import are there any standerds if yes which one to follow: Positions are manual-entry only for MVP, one lot per entry, never auto-averaged; import is extension-scope.
6) what is the featch cost : PriceHistory and Signal are both fetched/computed on demand, not pre-populated — the first viewer of a stock each day pays the (small) fetch cost, not a batch job run for stocks nobody looks at
7) Treated as extension-scope here. ------> is this part of full project or next version
8) Where we will use AI in the prject
