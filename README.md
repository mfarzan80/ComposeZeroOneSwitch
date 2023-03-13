# Jitpack Compose ZeroOneSwitch

## Usage

![ezgif-5-9f327823ac](https://user-images.githubusercontent.com/60168299/224626695-e6b09e8e-ed81-44dc-a264-f007cb2336f1.gif)


``` kotlin
var switchValue by remember { mutableStateOf(false) }
ZeroOneSwitch(
              checked = switchValue,
              colors = SwitchDefaults.colors(
              checkedTrackColor = Color(0xff468E8C),
              uncheckedTrackColor = Color(0xffFF6695),
              uncheckedTrackAlpha = 1f),
              onCheckedChange = {
                  switchValue = it
})

```
