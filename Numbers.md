# Snippets Involving Numbers
There are times where numbers get really large and a standard integer is not big enough to handle the number. Handling things like that are the types of snippets in this readme.
## Adding really large integers together

```csharp
long[] arrayConverted = Array.ConvertAll<int, long>(arr, delegate(int i){ return (long)i;});
        
var sum = arrayConverted.Sum();
Console.WriteLine($"{sum - arrayConverted.Max()} {sum - arrayConverted.Min()}");
```
## Finding the total of tallest candles.

```csharp
public static int birthdayCakeCandles(List<int> candles)
    {
        var tallest = candles.Max();
        int sum = 0;
        foreach(var can in candles){
            if(can == tallest){
                sum++;
            }
        }
        return sum;
    }
```
