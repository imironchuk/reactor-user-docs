# Target Preview on Android

Target Preview allows you to easily perform end-to-end QA for Target activities and preview these activities on your device.

For more information on how to set up and use Target Preview, go to [Target Mobile Preview](https://marketing.adobe.com/resources/help/en_US/target/target/target-mobile-preview.html).

## setPreviewRestartDeepLink

Sets an app deepLink that will be triggered when preview selections are applied in the Preview mode.

### Syntax

```java
public static void setPreviewRestartDeepLink(final Uri deepLink);
```

### Example

```java
Target.setPreviewRestartDeepLink("myApp://HomePage");
```

