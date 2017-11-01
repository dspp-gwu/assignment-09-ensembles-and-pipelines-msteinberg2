# Assignment 09: Ensemble models & pipelines
The final homework assignment for our class will introduce you to ensemble models and pipelines. 

An ensemble model combines more than one model to achieve better predictions along some desired metric or set of metrics.  Although there are an infinite number of potential ensemble models, the most commonly used class of ensembles is called a "random forest" model, and it combines many decisions trees (hence the "forest") into an "ensemble" of decision trees, with each tree "voting" for a specific outcome.  

Let's start with a very simple decision tree.  We want to know if an inspector will find an active rat burrow in a specific census track.  Let's start our tree with one feature: whether inspectors found an active rat burrow there the prior year. If yes, our decision tree tells us there will be rats there again this year; if not, then it tells us there will be no rats.  It may be better than nothing, but it's not very good.  OK, so let's add another feature. Are there restaurants present on that track?  If yes, then 
