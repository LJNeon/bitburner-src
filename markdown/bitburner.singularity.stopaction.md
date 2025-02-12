<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Singularity](./bitburner.singularity.md) &gt; [stopAction](./bitburner.singularity.stopaction.md)

## Singularity.stopAction() method

Stop the current action.

**Signature:**

```typescript
stopAction(): boolean;
```
**Returns:**

boolean

True if the player’s action is stopped, false if the player is not performing an action.

## Remarks

RAM cost: 1 GB \* 16/4/1

This function stops the action the player is currently performing. The player will receive rewards (money, experience, etc.) they have earned from that action.

The actions that can be stopped with this function are:

- Studying at a university

- Working out at a gym

- Working for a company/faction

- Creating a program

- Committing a crime

- Grafting an augmentation

This function will return true if the player's action is stopped. It will return false if the player is not performing an action when this function is called.

