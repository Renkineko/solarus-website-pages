Shortcodes
=================

Summary
-----------------
* [[alert]](shortcodes.md#alert)
* [[badge]](shortcodes.md#badge)
* [[button]](shortcodes.md#button)
* [[icon]](shortcodes.md#icon)
* [[space]](shortcodes.md#space)
* [[tweets]](shortcodes.md#tweets)
* [[tweet]](shortcodes.md#tweet)
* [[twitch]](shortcodes.md#twitch)
* [[youtube]](shortcodes.md#youtube)

[alert]
-----------------

**Name:** alert

**Use on the site:** All over

**Description:** Display a message as an alert.

**Content:** Yes

**Mandatory content:** Yes

**Parameters:**
* **dismiss**
    * **Mandatory:** No
    * **Possible values:** true|false
    * **Default value:** false
    * **Conditions of use:** None
    * **Sample:** `dismiss="true"`
* **icon**
    * **Mandatory:** No
    * **Possible values:** Fontawesome icon slug or false
    * **Default value:** false
    * **Conditions of use:** None
    * **Sample:** `icon="home"`
* **type**
    * **Mandatory:** No
    * **Possible values:** primary|secondary|success|danger|warning|info|light|dark
    * **Default value:** primary
    * **Conditions of use:** None
    * **Sample:** `type="primary"`

**Sample:**
`[alert dismiss="true" icon="home" type="success"]Content[/alert]`


[badge]
-----------------

**Name:** badge

**Use on the site:** All over

**Description:** Display a small badge.

**Content:** Yes

**Mandatory content:** Yes

**Parameters:**
* **icon**
    * **Mandatory:** No
    * **Possible values:** Fontawesome icon slug or false
    * **Default value:** false
    * **Conditions of use:** None
    * **Sample:** `icon="home"`
* **type**
    * **Mandatory:** No
    * **Possible values:** primary|secondary|success|danger|warning|info|light|dark
    * **Default value:** primary
    * **Conditions of use:** None
    * **Sample:** `type="primary"`

**Sample:**
`[badge type="success" icon="home"]New[/badge]`

[button]
-----------------

**Name:** button

**Use on the site:** All over

**Description:** Display a button 

**Content:** Yes

**Mandatory content:** Yes

**Parameters:**
* **icon**
    * **Mandatory:** No
    * **Possible values:** Fontawesome icon slug or false
    * **Default value:** false
    * **Conditions of use:** None
    * **Sample:** `icon="home"`
* **link**
    * **Mandatory:** No
    * **Possible values:** Absolute/relative url or false
    * **Default value:** false
    * **Conditions of use:** None
    * **Sample:** `link="http://www.zelda-solarus.com"`
* **outline**
    * **Mandatory:** No
    * **Possible values:** true|false
    * **Default value:** false
    * **Conditions of use:** None
    * **Sample:** `outline="true"`
* **size**
    * **Mandatory:** No
    * **Possible values:** sm|md|lg
    * **Default value:** md
        * **Conditions of use:** None
    * **Sample:** `size="lg"`
* **target**
    * **Mandatory:** No
    * **Possible values:** _parent|_blank
    * **Default value:** _parent
    * **Conditions of use:**
        * The "link" parameter must not be empty
    * **Sample:** `target="_blank"
* **type**
    * **Mandatory:** No
    * **Possible values:** primary|secondary|success|danger|warning|info|light|dark
    * **Default value:** primary
    * **Conditions of use:** None
    * **Sample:** `type="primary"`

**Sample:**
`[badge type="success" icon="home"]New[/badge]`

[icon]
-----------------

**Name:** icon

**Use on the site:** All over

**Description:** Display an icon

**Content:** No

**Mandatory content:** No

**Parameters:**
* **icon**
    * **Mandatory:** Yes
    * **Possible values:** Fontawesome icon slug or false
    * **Default value:** false
    * **Conditions of use:** None
    * **Sample:** `icon="home"`

**Sample:**
`[icon icon="home"]`


[space]
-----------------

**Name:** space

**Use on the site:** All over

**Description:** Display a space

**Content:** No

**Mandatory content:** No

**Parameters:**
* **height**
    * **Mandatory:** No
    * **Possible values:** height in pixels
    * **Default value:** 10
    * **Conditions of use:** None
    * **Sample:** `height="20"`

**Sample:**
`[space height="20"]`


[youtube]
-----------------

**Name:** youtube

**Use on the site:** All over

**Description:** Display a youtube video 

**Content:** No

**Mandatory content:** No

**Parameters:**
* **id**
    * **Mandatory:** Yes
    * **Possible values:** Youtube id
    * **Default value:** false
    * **Conditions of use:** None
    * **Sample:** `id="7GR308Ox-8o"`
* **allowfullscreen**
    * **Mandatory:** No
    * **Possible values:** true|false
    * **Default value:** true
    * **Conditions of use:** None
    * **Sample:** `allowfullscreen="false"`

**Sample:**
`[youtube allowfullscreen="false" id="7GR308Ox-8o"]`