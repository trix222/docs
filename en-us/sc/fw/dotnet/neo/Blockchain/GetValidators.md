# Blockchain.GetValidators method ()

Get the public key of the consensus person.

Namespace: [Neo.SmartContract.Framework.Services.Neo](../../neo.md)

Assembly: Neo.SmartContract.Framework

## syntax

```c#
public static extern byte[][] GetValidators ()
```

Return Value: A public key array, each element in the array is a 33-byte byte array.

## example

```c#
public class Contract1: FunctionCode
{
     public static void Main ()
     {
         byte[][] validators = Blockchain.GetValidators ();
     }
}
```



[Return to superior](../Blockchain.md)
