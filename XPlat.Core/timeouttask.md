# TimeoutTask class

> Namespace: XPlat.Threading.Tasks

Defines a task that is actioned when the timeout occurs unless cancelled.

```csharp
public class TimeoutTask
```

## Supported platforms

| Platform | Version |
| --- | --- |
| .NET Standard | 1.4 |
| Xamarin.Android | 8.1 |
| Xamarin.iOS  | 1.0 |
| UWP | 10.0 | 

## Constructors

### TimeoutTask(TimeSpan, Action)

#### Parameters
##### timeout (TimeSpan)
The timeout period.
##### timeoutAction (Action)
The action to perform when the timeout occurs.

## Methods

### Cancel()

Cancels the timeout task to prevent the timeout action from occurring.

```csharp
public void Cancel()
```