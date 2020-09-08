# NHS Virtual Visits Serverless

A WIP to pave the way for the moving of NHS VV to serverless.

## Serverless

The application can be ran locally using:

```
sls invoke local --function functionName
```

Currently, there are functions for GET and POST, in `/api/candidate.js`. These are currently only placeholders, but 
demonstrate suitable techniques we can use going forward. 

The application can be deployed manually using:

```
sls deploy
```

**WARNING** this will deploy to whatever AWS profile is currently active on your machine
without warning and WILL overwrite anything currently deployed on the same stack. Use with care.

## TODO

- Change placeholders for something more NHS VV specific?
- Implement a transpiler allowing for ES6 goodness. 
- Try hooking in with serverless express/next.js.
- Automate the serverless deployments.
