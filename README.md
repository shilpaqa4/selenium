# Playwright Automation – SDET Screening

This project demonstrates browser automation using **Playwright**.

## Test Steps Automated
1. Navigate to booking website
2. Click "Complete booking"
3. Select party size = 3
4. Select dining date = Feb 11
5. Select time = 12:00
6. Click "Complete booking" 
7. Capture  video
8. Cpature screenshot 

## How to Run
```
open folder in vs code 
npx playwright test Complete_booking_video.spec.ts
npx playwright test Complete_booking_screenshot.spec.ts

```

## Output
After execution, screenshots stored in screenshots folder  is generated showing the completed booking form.

## Tech Used
-typescript
- Playwright
