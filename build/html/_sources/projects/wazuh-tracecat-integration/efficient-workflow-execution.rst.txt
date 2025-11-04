Efficient Workflow Execution
============================

So far what we have discussed and implemented, it's a foundation for our overall workflow. What you are seeing here is that,
it's a functional workflow meant to execute every component whenever the workfolow will run. If we run the workflow now,
it will execute all its components regardless if there was any attack and the active response scripts will be initiated on
the endpoints without and actual valid attacker IP.

This is where we want to make the workflow dynamic where, the conditional executions will come in handy.