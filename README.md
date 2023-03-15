# Pedometer
> The pedometer is an electronic device that counts the number of steps taken. Nowadays, almost all mobile phones, smart watches, and fitness gear come with pedometers built into them. The health and fitness app uses built-in pedometers to calculate the number of steps taken. This function calculates the number of calories that the user burns based on the user's number of steps
>
 I created this repo while undertaking my **Android Basics** with **Kotlin** journey ***@Googledev***

 ## Step One
 Create Two variables ie one for sstoring number of steps and the other for amount of calories burned.
```

    var steps.
    var caloriesBurned.
```

## Step Two

Create a function ***pedometerStepsTOcalories()*** that takes number of syeps as a parameter and returns TotalCALORIESburned as a result of numberOfsteps multiplied by calories burned.

```
fun pedometerStepsTOcalories(NumberOFStepS: Int): Double {
    val CaloriesBURNEDforEachStep = 0.04
    val TotalCALORIESburned = NumberOFStepS * CaloriesBURNEDforEachStep
    return TotalCALORIESburned
}
```

## Final Step 
Create main function that calls the ***pedometerStepsTOcalories() function***

**Implementation**

```
fun main() {
    val Steps = 4000
    val caloriesBurned = PEDOMETERstepsTOcalories(Steps);
    println("Walking $Steps steps burns $caloriesBurned calories") 
}

fun pedometerStepsTOcalories(NumberOFStepS: Int): Double {
    val CaloriesBURNEDforEachStep = 0.04
    val TotalCALORIESburned = NumberOFStepS * CaloriesBURNEDforEachStep
    return TotalCALORIESburned
}

```
