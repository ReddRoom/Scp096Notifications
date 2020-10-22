## Scp096 Notifications
Display notifications when a user views SCP-096's face (and display a message to SCP-096 when they gain a new target).

## Configs
| Name                         | Type   | Default                                                        | Description                                                                                                                                 |
|------------------------------|--------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| is_enabled                   | bool   | true                                                           | Enables the plugin.                                                                                                                         |
| enable096_seen_message       | bool   | true                                                           | Determines whether or not players will be notified upon viewing SCP-096's face.                                                             |
| enable096_new_target_message | bool   | true                                                           | Determines whether or not SCP-096 will be notified upon receiving a new target.                                                             |
| scp096_seen_message          | string | You are a target of SCP-096!                                   | Message to display to targets upon viewing SCP-096's faces.                                                                                 |
| scp096_new_target_message    | string | <b>{name}</b> has viewed your face! They are a <b>{class}</b>. | Message to display to SCP-096 upon receiving a new target. {name} changes to the player's name and {class} changes to their class (colored) |