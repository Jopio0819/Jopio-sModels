# Turning off 1 zone

```lua
function Off()
local model = game.Workspace["Jopio's Light System"]
local api = model.Zones.Trigger

	api:Fire("Off","ZONE NUMBER")
end

-- Your logic here, to fire the function.
```

{% hint style="danger" %}
Dont forget to add the "" for the zone. Else the system will crash.
{% endhint %}
