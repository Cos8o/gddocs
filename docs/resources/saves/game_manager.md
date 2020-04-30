# GameManager File Structure

Note: this section is incomplete.

| Key           | Type          | Description  |
| ------------- | ------------- | ------------ |
| valueKeeper   | **dictionary**     | Big dictionary that holds game variables and unlocked stuff. |
| unlockValueKeeper     | **dictionary**     |  Other dictionary that holds unlocked features in game. |
| customObjectDict | **dictionary** | *unknown* |
| bgVolume | **float** | Music volume |
| sfxVolume | **float** | Sound effects volume |
| timeOffset | **integer** | *unknown*, probably delay setting |
| playerUDID | **string** | The player's UDID (add link) |
| playerName | **string** | The player's username |
| playerUserID | **integer** | The player's User ID |
| playerFrame | **integer** | The player's icon |
| playerShip | **integer** | The player's ship |
| playerBall | **integer** | The player's ball |
| playerBird | **integer** | The player's ufo |
| playerDart | **integer** | The player's wave |
| playerRobot | **integer** | The player's robot |
| playerSpider | **integer** | The player's spider |
| playerColor | **integer** | The player's color |
| playerColor2 | **integer** | The player's second color |
| playerStreak | **integer** | The player's streak |
| playerDeathEffect | **integer** | The player's death effect |
| playerGlow | **boolean** | Whether the glow effect is enabled or not |
| secretNumber | **integer** | *unknown* |
| hasRP | **boolean** | *unknown* |
| reportedAchievements | **dictionary** | List of achievements. Every entry is a dictionary made of the achievement id (**string**), and its percentage (**integer**). |
| GJA_001 | **string** | The account's username |
| GJA_002 | **string** | The account's password (it's plain text :v) |
| GJA_003 | **integer** | The account's id |
| showSongMarkers | **boolean** | Show guidelines in the editor |
| showBPMMarkers | **boolean** | Show blue lines in the editor accurately indicating the start of the beat; discarded in new versions of the game |
| recordGameplay | **boolean** | everyplay |
| showProgressBar | **boolean** | Show the progress bar in-game |
| performanceMode | **boolean** | *unknown* |
| clickedGarage | **boolean** | Whether you've entered the icon screen once, or not; used to display the relative text on the main menu |
| clickedEditor | **boolean** | *Fuck do i know* |
| clickedName | **boolean** | *Fuck do i know* |
| clickedPractice | **boolean** | *Fuck do i know* |
| showedEditorGuide | **boolean** | *Fuck do i know* |
| showedRateDiffDialog | **boolean** | *Fuck do i know* |
| showedRateStarDialog | **boolean** | *Fuck do i know* |
| showedLowDetailDialog | **boolean** | *Fuck do i know* |
| bootups | **integer** | How many times you've started GD |
| hasRatedGame | **boolean** |  |
| binaryVersion | **integer** | binaryVersion |
| resolution | **integer** | resolution |
| texQuality | **integer** | texQuality |

# Game Variables

Game variables are all booleans.

|  Name   | Description |
|  ----   | ----------- |
| gv_0001 | followPlayer (editor)
| gv_0002 | playtestMusic (editor)
| gv_0003 | toggleSwipe (editor)
| gv_0004 | toggleFreeMove (editor)
| gv_0007 | toggleRotate (editor)
| gv_0008 | toggleSnap (editor)
| gv_0009 | ignoreDamage (editor)
| gv_0010 | flip2PlayerControls
| gv_0011 | alwaysLimitControls
| gv_0013 | increaseMaxUndoRedo
| gv_0014 | disableExplosionShake
| gv_0015 | flipPauseButton
| gv_0018 | noSongLimit
| gv_0019 | songsInMemory
| gv_0020 | [UNUSED]
| gv_0021 | [UNUSED]
| gv_0022 | higherAudioQuality
| gv_0023 | smoothFix
| gv_0024 | showCursorInGame (?)
| gv_0025 | fullscreenMode
| gv_0026 | autoRetry
| gv_0027 | autoCheckpoints
| gv_0029 | showedOptionsText
| gv_0030 | vsyncEnabled
| gv_0031 | callGLFinish (?)
| gv_0032 | forceTimerEnabled (?)
| gv_0033 | useOtherSongPath
| gv_0034 | gameCenterEnabled
| gv_0035 | [UNUSED]
| gv_0036 | previewMode (editor)
| gv_0037 | showGround (editor)
| gv_0038 | showGrid (editor)
| gv_0039 | gridOnTop (editor)
| gv_0040 | showPercentage
| gv_0041 | showObjectInfo (editor)
| gv_0042 | increaseMaxLevels
| gv_0043 | effectLinesEnabled (editor)
| gv_0044 | drawTriggerBoxes (editor)
| gv_0045 | debugDraw (editor)
| gv_0046 | hideUIOnTest (editor)
| gv_0047 | showedProfileText
| gv_0049 | buttonsPerRow (editor)
| gv_0050 | buttonRows (editor)
| gv_0051 | showedNGMessage (editor)
| gv_0052 | fastPracticeReset
| gv_0054 | [UNUSED]
| gv_0056 | disableObjectAlert
| gv_0057 | editorHoldToSwipe
| gv_0058 | durationLines (editor)
| gv_0059 | swipeCycleMode
| gv_0060 | defaultMiniIcon
| gv_0061 | switchSpiderTeleportColor
| gv_0062 | switchDashFireColor
| gv_0063 | showedUnverifiedCoinsMessage
| gv_0064 | selectFilter (editor)
| gv_0065 | enableMoveOptimization
| gv_0066 | highCapacityMode
| gv_0067 | highStartPosAccuracy
| gv_0068 | quickCheckpointMode
| gv_0070 | showedUnlistedLevelMessage
| gv_0071 | [UNUSED]
| gv_0072 | disableGravityEffect
| gv_0073 | newCompletedFilter
| gv_0074 | showRestartButton
| gv_0075 | disableComments
| gv_0076 | disableAccountComments
| gv_0077 | featuredLevelsOnly
| gv_0078 | hideBackground (editor)
| gv_0079 | hideGridOnPlay (editor)
| gv_0080 | [UNUSED
| gv_0081 | disableShakeEffects
| gv_0082 | disableHighObjectAlert
| gv_0083 | disableSongAlert
| gv_0084 | manualOrder
| gv_0085 | [UNUSED]
| gv_0086 | [UNUSED]
| gv_0087 | [UNUSED]
| gv_0088 | smallCommentsMode
| gv_0089 | extendedInfoMode
| gv_0090 | autoloadComments
| gv_0093 | increaseLocalLevelsPerPage
| gv_0094 | moreCommentsMode
| gv_0095 | flippyUselessMode
| gv_0096 | switchWaveTrailColor
| gv_0097 | enableLinkControls (editor)
| gv_0098 | levelLeaderboardType
| gv_0099 | showLeaderboardPercent
| gv_0100 | practiceDeathEffect
| gv_0101 | forceSmoothFix
| gv_0102 | smoothFixInEditor| gv_0014 | disableExplosionShake
| gv_0015 | flipPauseButton
| gv_0018 | noSongLimit
| gv_0019 | songsInMemory
| gv_0020 | [UNUSED]
| gv_0021 | [UNUSED]
| gv_0022 | higherAudioQuality
| gv_0023 | smoothFix
| gv_0024 [TO CHECK] | showCursorInGame
| gv_0025 | fullscreenMode
| gv_0026 | autoRetry
| gv_0027 | autoCheckpoints
| gv_0029 | showedOptionsText
| gv_0030 | vsyncEnabled
| gv_0031 | callGLFinish (?)
| gv_0032 | forceTimerEnabled (?)
| gv_0033 | useOtherSongPath
| gv_0034 | gameCenterEnabled
| gv_0035 | [UNUSED]
| gv_0036 | previewMode (editor)
| gv_0037 | showGround (editor)
| gv_0038 | showGrid (editor)
| gv_0039 | gridOnTop (editor)
| gv_0040 | showPercentage
| gv_0041 | showObjectInfo (editor)
| gv_0042 | increaseMaxLevels
| gv_0043 | effectLinesEnabled (editor)
| gv_0044 | drawTriggerBoxes (editor)
| gv_0045 | debugDraw (editor)
| gv_0046 | hideUIOnTest (editor)
| gv_0047 | showedProfileText
| gv_0049 | buttonsPerRow (editor)
| gv_0050 | buttonRows (editor)
| gv_0051 | showedNGMessage (editor)
| gv_0052 | fastPracticeReset
| gv_0054 | [UNUSED]
| gv_0056 | disableObjectAlert
| gv_0057 | editorHoldToSwipe
| gv_0058 | durationLines (editor)
| gv_0059 | swipeCycleMode
| gv_0060 | defaultMiniIcon
| gv_0061 | switchSpiderTeleportColor
| gv_0062 | switchDashFireColor
| gv_0063 | showedUnverifiedCoinsMessage
| gv_0064 | selectFilter (editor)
| gv_0065 | enableMoveOptimization
| gv_0066 | highCapacityMode
| gv_0067 | highStartPosAccuracy
| gv_0068 | quickCheckpointMode
| gv_0070 | showedUnlistedLevelMessage
| gv_0071 | [UNUSED]
| gv_0072 | disableGravityEffect
| gv_0073 | newCompletedFilter
| gv_0074 | showRestartButton
| gv_0075 | disableComments
| gv_0076 | disableAccountComments
| gv_0077 | featuredLevelsOnly
| gv_0078 | hideBackground (editor)
| gv_0079 | hideGridOnPlay (editor)
| gv_0080 | [UNUSED
| gv_0081 | disableShakeEffects
| gv_0082 | disableHighObjectAlert
| gv_0083 | disableSongAlert
| gv_0084 | manualOrder
| gv_0085 | [UNUSED]
| gv_0086 | [UNUSED]
| gv_0087 | [UNUSED]
| gv_0088 | smallCommentsMode
| gv_0089 | extendedInfoMode
| gv_0090 | autoloadComments
| gv_0093 | increaseLocalLevelsPerPage
| gv_0094 | moreCommentsMode
| gv_0095 | flippyUselessMode
| gv_0096 | switchWaveTrailColor
| gv_0097 | enableLinkControls (editor)
| gv_0098 | levelLeaderboardType
| gv_0099 | showLeaderboardPercent
| gv_0100 | practiceDeathEffect
| gv_0101 | forceSmoothFix
| gv_0102 | smoothFixInEditor

# ValueKeeper Values

- Game variables
- Unlocked icons
  - Cubes (i_XXX)
  - Ships (ship_XXX),
  - Balls (ball_XXX),
  - UFOs (bird_XXX),
  - Waves (dart_XXX),
  - Robots (robot_XXX),
  - Spiders (spider_XXX)
- Unlocked streaks (special_XXX)
- Unlocked colors (c0_XXX, c1_XXX)
- Unlocked death effects (death_XXX)

# UnlockValueKeeper Values

UnlockValueKeeper variables are all booleans.

| Name | Description |
| ---- | ----------- |
| ugv_1 | the challenge unlocked
| ugv_2 | given glubfub hint (keymaster)
| ugv_3 | given glubfub hint (the guard)
| ugv_4 | the challenge completed/demon room unlocked
| ugv_5 | treasure room unlocked
| ugv_6 | chamber of time unlocked
| ugv_7 | chamber of time discovered
| ugv_8 | shown master emblem to gatekeeper
| ugv_9 | gatekeeper dialog shown
| ugv_10 | scratch dialog shown
| ugv_11 | secret shop unlocked
| ugv_12 | talked with demon guardian
| ugv_13 | demon freed
| ugv_14 | has first demon key
| ugv_15 | has second demon key
| ugv_16 | has third demon key
| ugv_17 | shopkeeper 500 orbs box shown
| ugv_18 | online levels unlocked (GD World)
| ugv_19 | idk, something related to the demon room
| ugv_20 | community shop unlocked
| ugv_21 | potbor dialog shown 
| ugv_22 | is youtube chest unlocked
| ugv_23 | is facebook chest unlocked
| ugv_24 | is twitter chest unlocked