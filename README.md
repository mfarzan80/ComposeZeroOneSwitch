# Jitpack Compose ZeroOneSwitch

## Usage

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
