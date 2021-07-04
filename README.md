# RollbackGgpoWithEcsExampleCsharp

This is an example project I created for using rollback and custom ecs

The ecs is designed arround rollback netcode and having many different object with different data. It uses reflection to keep save and load the data for every component.

The same reflection values can be used to detect which property caused the desync.
(This example includes the code for the desync detection aswell)

This example uses unity but the ecs code can be used in any c# environment that allows reflections.

It uses nykwil's ggpo wrapper for unity
https://github.com/nykwil/UnityGGPO