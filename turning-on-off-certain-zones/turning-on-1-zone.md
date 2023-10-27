# Turning on 1 zone

```lua
function On()
local model = game.Workspace["Jopio's Light System"]
local api = model.Zones.Trigger

	api:Fire("On","ZONE NUMBER")
end

-- Your logic here, to fire the function.
```

{% hint style="danger" %}
Dont forget to add the "" for the zone. Else the system will crash.
{% endhint %}
