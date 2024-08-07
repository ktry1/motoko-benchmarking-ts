[**motoko-benchmarking-ts v1.0.0**](../README.md) • **Docs**

***

[motoko-benchmarking-ts v1.0.0](../README.md) / makeActor

# Function: makeActor()

> **makeActor**\<`_SERVICE`\>(`agent`, `idlFactory`, `canisterId`): `ActorSubclass`\<`_SERVICE`\>

A function to create an actor for calling the local canister

## Type Parameters

• **_SERVICE**

## Parameters

• **agent**: `HttpAgent`

an agent for interacting with local dfx environment.

• **idlFactory**: `InterfaceFactory`

idlFactory imported from canister declaration

• **canisterId**: `string`

canister id of a deployed canister

## Returns

`ActorSubclass`\<`_SERVICE`\>

actor - an actor to interact with local canister

## Defined in

index.ts:79
