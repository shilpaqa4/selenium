# Playwright C# Automation – SDET Screening

This project demonstrates browser automation using **Playwright with C#**.

## Test Steps Automated
1. Navigate to booking website
2. Click "Complete booking"
3. Select party size = 3
4. Select dining date = Feb 11
5. Select time = 12:00
6. Capture screenshot

## How to Run
```
dotnet restore
playwright install
dotnet run
```

## Output
After execution, `booking_result.png` is generated showing the completed booking form.

## Tech Used
- C#
- Playwright
- .NET
