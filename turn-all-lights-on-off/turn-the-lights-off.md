# Turn the lights off

Your code should look a bit like this when you try to turn the lights off.

```lua
function Off()
local model = game.Workspace["Jopio's Light System"]
local api = model.Zones.Trigger

	api:Fire("Off","0")
end

-- Your logic here, to fire the function.
```

{% hint style="danger" %}
Dont forget to add the "" for the zone. Else the system will crash.
{% endhint %}
