# Turn the lights on

In order to set the lights on, your script should look a bit like this:

```lua
function On()
local model = game.Workspace["Jopio's Light System"]
local api = model.Trigger

	api:Fire("On")
end

-- Your logic here, to fire the function.
```

It is very easy, and can be done by anyone!
