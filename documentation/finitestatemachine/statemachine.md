---
description: serializable class
---

# Class StateMachine

Class for create a state machine at runtime

### **Variables**

| Name | Type | Description |
| :--- | :--- | :--- |
| **isRunning** | bool | Is the state machine running? |
|  |  |  |

### **Methods**

| Name | Return | Description |
| :--- | :--- | :--- |
| **InitStateMachine**\( \) | void | Initialize machine with states and transitions |
| InitStateMachine\(float param \) |  |  |
| **RunStateMachine**\( \) | void | Start update behaviour |

## **How to use**

Se usa asi:

```csharp
for (int i = 0 ; i < 10; i++)
{
    InitStateMachine();// Code to execute.
}
```



