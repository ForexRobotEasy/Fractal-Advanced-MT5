# Fractal Advanced MT5

This code is a sample implementation of the Fractal Advanced MT5 indicator developed by the Forex Robot Easy Team. The indicator utilizes the Fractals and Alligator indicators to perform market analysis and provide signals on the chart.

## Global Variables
- `maxFractals`: The maximum number of fractals to display on the chart.
- `enableAlerts`: A boolean variable to enable or disable custom alerts.
- `enableHotkeys`: A boolean variable to enable or disable hotkeys.

## Custom Alerts System
The `CustomAlert` function is responsible for displaying custom alerts. If `enableAlerts` is set to true, the function will display an alert message and play a sound.

## Hotkey System
The `OnChartEvent` function handles the hotkey system. If `enableHotkeys` is set to true, the function will check for specific key combinations and perform corresponding actions. Currently, the code is set to perform actions for F1 and F2 hotkeys, but more hotkeys can be added as needed.

## Initialization and Deinitialization
The `OnInit` function is called during the indicator's initialization. It sets the number of fractals to display on the chart using the `ChartSetInteger` function.

The `OnDeinit` function is called during the indicator's deinitialization. It allows for necessary cleanup before closing the program.

## Start Function
The `OnStart` function is the main function of the indicator. It performs market analysis using the Fractal and Alligator indicators, displays relevant fractal signals on the chart, and allows for adjusting the number of fractals on the chart by scrolling the mouse while holding down the Shift key.

The code also mentions the implementation of a custom alerts system for important market events and a hotkey system for quick access to important features and functions. It emphasizes the importance of thorough testing and compatibility with the MT5 trading platform. Clear and concise code documentation is also mentioned for easy understanding and future maintenance.

Please note that ForexRobotEasy is not the official developer of this product. This code is only a sample implementation that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/fractal-advanced-mt5-review-forex-software-with-custom-alerts-and-settings/).
