<p align="center">
    <img src="res/portraits/sonic.png">
    <h1 align="center" class="charName">Sonic The Hedgehog</h1>
    <table align="center">
        <tr>
            <td>Selectable</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td>Associated Stage</td>
            <td><a href="?a=stages/emeraldbeach">Emerald Beach</a></td>
        </tr>
        <tr>
            <td>Slot</td>
            <td>01</td>
        </tr>
    </table> 
</p>

Sonic is an all rounder character designed for beginners, with relatively straight forward moves mapped to all buttons and not many special mechanics. On the technical end, Sonic begins the bulk of character related sets of data and is typically the character used to test this data.

## Moveset

### Standard Combo

<table class="movedata">
    <tr>
        <th>Info</th>
        <th>Damage</th>
        <th>Start-up</th>
        <th>Active</th>
        <th>Recovery</th>
    </tr>
    <tr>
        <td>
            <img src="res/portraits/sonic.png">
            <br>
            A basic, incredibly weak punch.
        </td>
        <td>--</td>
        <td>8</td>
        <td>2</td>
        <td>5</td>
    </tr>
</table> 

## Technical Data

Below is a list of this characters technical data for modders. 

### Graphics

| Graphic | Graphic Address | Palette Address | Compressed? | Compressed Index | Tile Width | Tile Height | Notes |
|--------:|:---------------:|:---------------:|:-----------:|:----------------:|:----------:|:-----------:|:------|
| Battle Mode Portrait | ``0x118B68`` | ``0x10DD04`` | Yes | 28 | 8 | 10 | See [Battle Portraits](?a=formats/portraits#battle).
| Spritesheet | ``0x47AFD8`` | ``0x47AFB8`` | No | | -- | -- | See [Character Sprites](?a=formats/charactersprites).
| Story Mode Map Spritesheet | ``0x184C6C`` | ``0x184C4C`` | Yes | 369 | 4 | 36 | See [Character Sprites](?a=formats/charactersprites).
| Life Icon | ``0x3251D4`` | ``0x47AFB8`` | No | | 2 | 2 |
| Lifebar | ``0x322154`` | ``0x47AFB8`` | No | | 8 | 4 |
| Neutral (Story) | ``0x1AA97C`` |``0x1AA95C`` | Yes | 399 | 8 | 18 | See [Story Portraits](?a=formats/portraits#story).
| Ready (Story) | ``0x1AB020`` |``0x1AA95C`` | Yes | 400 | 8 | 18 | See [Story Portraits](?a=formats/portraits#story).
| Shrug (Story) | ``0x1AB6CC`` |``0x1AA95C`` | Yes | 401 | 8 | 18 | See [Story Portraits](?a=formats/portraits#story).
| Ready (Pointing) (Story) | ``0x1ABD60`` |``0x1AA95C`` | Yes | 402 | 8 | 18 | See [Story Portraits](?a=formats/portraits#story).
| Challenge Mode Portrait | ``0x12034C`` | | Yes | 48 | ? | ? | Unknown format and layout.

### Animation Data

| Animation | Animation Address | Pointer Address |
|:----------|:-----------------:|:---------------:|
| Idle | ``0x00052F7C`` | ``0x00ED68A8`` |
| Running | ``0x00052FD4`` | ``0x00ED68AC`` |
| Possible running loop? | ``0x00053044`` | ``0x00ED68B0`` |
| Stopping | ``0x0005308C`` | ``0x00ED68B4`` |
| Dash | ``0x000530C8`` | ``0x00ED68B8`` |
| Running turn around | ``0x00053158`` | ``0x00ED68BC`` |
| Standing turn around | ``0x0005318C`` | ``0x00ED68C0`` |
| Falling | ``0x000531C0`` | ``0x00ED68C4`` |
| Jumping | ``0x00053238`` | ``0x00ED68C8`` |
| Landing | ``0x00053284`` | ``0x00ED68CC`` |
| Air dash | ``0x000532C0`` | ``0x00ED68D0`` |
| Standard combo 1 | ``0x00053334`` | ``0x00ED68D4`` |
| Standard combo 2 | ``0x000533AC`` | ``0x00ED68D8`` |
| Standard combo 3 | ``0x00053424`` | ``0x00ED68DC`` |
| Heavy attack | ``0x000534AC`` | ``0x00ED68E0`` |
| Upper attack | ``0x000535A0`` | ``0x00ED68E4`` |
| Dash attack | ``0x0005362C`` | ``0x00ED68E8`` |
| Eagle Kick (Pursuit attack) | ``0x000536B0`` | ``0x00ED68EC`` |
| Eagle Kick (Standard) | ``0x000537A0`` | ``0x00ED68F0`` |
| Unknown variant of Eagle Kick | ``0x00053818`` | ``0x00ED68F4`` |
| Air attack | ``0x0005389C`` | ``0x00ED68F8`` |
| Shot attack (Left/Right) | ``0x00053914`` | ``0x00ED68FC`` |
| Unknown cut into a fall | ``0x00053A20`` | ``0x00ED6900`` |
| Unknown cut into a fall (2) | ``0x00053A28`` | ``0x00ED6904`` |
| Unknown left/right shot/spindash data | ``0x00053A30`` | ``0x00ED6908`` |
| Ground Power attack (Ring throw) | ``0x00053B38`` | ``0x00ED6914`` |
| Shot attack (Down) | ``0x00053BAC`` | ``0x00ED6918`` |
| Unknown idle reset | ``0x00053C98`` | ``0x00ED691C`` |
| Aerial trap | ``0x00053CA0`` | ``0x00ED6920`` |
| Unknown down shot/spindash data | ``0x00053D78`` | ``0x00ED6924`` |
| Grounded Trap | ``0x00053E2C`` | ``0x00ED692C`` |
| Unknown idle reset | ``0x00053EB4`` | ``0x00ED6934`` |
| Weird idle->punch->aerial flicker animation | ``0x00053EBC`` | ``0x00ED6938`` |
| Unknown idle reset | ``0x00053F48`` | ``0x00ED6940`` |
| Getting hit | ``0x00053F50`` | ``0x00ED6944`` |
| Getting flung back | ``0x00053F8C`` | ``0x00ED6948`` |
| Unknown but related getting hit animation | ``0x0005417C`` | ``0x00ED694C`` |
| Unknown but related getting hit animation | ``0x000541CC`` | ``0x00ED6950`` |
| Getting knocked into the air | ``0x0005408C`` | ``0x00ED6954`` |
| Unknown but related to getting knocked into the air | ``0x00054104`` | ``0x00ED6958`` |
| Getting back up | ``0x00054214`` | ``0x00ED695C`` |
| Seemingly a duplicate of Getting Back Up | ``0x00054268`` | ``0x00ED6960`` |
| Landing (After being hit) | ``0x000542CC`` | ``0x00ED6964`` |
| Getting back up (After landing after being hit) | ``0x000543C0`` | ``0x00ED6968`` |
| Unknown but related to being launched into the air | ``0x0005441C`` | ``0x00ED696C`` |
| More of getting flung back | ``0x00054490`` | ``0x00ED6970`` |
| Knocked back into the air and falling (?? | ``0x000545A4`` | ``0x00ED6978`` |
| Getting hit normally then getting back up? | ``0x00054618`` | ``0x00ED697C`` |
| Knocked into the air? | ``0x0005467C`` | ``0x00ED6980`` |
| Related to getting backup? | ``0x000546F4`` | ``0x00ED6984`` |
| Start to get back then initiate idle? | ``0x0005472C`` | ``0x00ED6988`` |
| More getting back on feet? | ``0x00054798`` | ``0x00ED698C`` |
| First two frames of getting back on feet? | ``0x000547D0`` | ``0x00ED6990`` |
| Possible duplicate of getting back on feet? | ``0x000547F8`` | ``0x00ED6994`` |
| Shield stun | ``0x00054818`` | ``0x00ED6998`` |
| Healing startup (First frame) | ``0x00054858`` | ``0x00ED699C`` |
| Healing loop | ``0x00054870`` | ``0x00ED69A0`` |
| Healing end | ``0x000548C8`` | ``0x00ED69A4`` |
| Wall jump | ``0x0005490C`` | ``0x00ED69A8`` |
| First two frames of being knocked into the air looped | ``0x00054924`` | ``0x00ED69AC`` |
| Landing then death animation | ``0x0005499C`` | ``0x00ED69B0`` |
| Respawn icon | ``0x00054A0C`` | ``0x00ED69B8`` |

