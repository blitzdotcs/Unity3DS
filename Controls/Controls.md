### 3DS Controls

* Since the basic Unity N3DS guide doesn't provide the actual functions for the controls I thought I'd share them here

* MAKE SURE TO ADD "using UnityEngine.N3DS;" IN YOUR SCRIPT

## Horizontal and Vertical Movement (CIRCLE PAD)

* Horizontal Movement - GamePad.CirclePad.x;

* Vertical Movement GamePad.CirclePad.y;

## Buttons

* A Button - GamePad.GetButtonRelease(N3dsButton.A)      and     GamePad.GetButtonHold(N3dsButton.A)
* B Button - GamePad.GetButtonRelease(N3dsButton.B)      and     GamePad.GetButtonHold(N3dsButton.B)
* X Button GamePad.GetButtonRelease(N3dsButton.X)        and     GamePad.GetButtonHold(N3dsButton.X)
* Y Button - GamePad.GetButtonRelease(N3dsButton.Y)      and     GamePad.GetButtonHold(N3dsButton.Y)
* L Button - GamePad.GetButtonRelease(N3dsButton.L)      and     GamePad.GetButtonHold(N3dsButton.L)
* R Button - GamePad.GetButtonRelease(N3dsButton.R)      and     GamePad.GetButtonHold(N3dsButton.R)
* ZL Button - GamePad.GetButtonRelease(N3dsButton.ZL)    and     GamePad.GetButtonRelease(N3dsButton.ZL)
* ZL Button - GamePad.GetButtonRelease(N3dsButton.ZR)    and     GamePad.GetButtonRelease(N3dsButton.ZR)
* Start Button - GamePad.GetButtonRelease(N3dsButton.Start)      and     GamePad.GetButtonHold(N3dsButton.Start)