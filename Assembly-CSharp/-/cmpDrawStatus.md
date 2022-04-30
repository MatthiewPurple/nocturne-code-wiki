# Summary
- Description 
- Fields
- Methods

# Description
UI rendering of the submenus

# Fields

# Methods
## static void cmpStatSetCompareUnit(datUnitWork_t pStock)

## static void cmpStatSetRaceEffect()

## static void cmpStatResetRaceEffect()

## static void cmpStatSetSkillEffectPos(sbyte Pos)

## static void cmpStatResetFlashFlag(sbyte Type)

## static int cmpStatSetTimer(int Time, sbyte Type)

## static void cmpStatMakeBlinkCol(int Val, sbyte Mode, uint[] pCol)

## static uint cmpGetStatusFontCol(uint[] pBaseCol, uint SrcCol)

## static void cmpDrawRestPoint(int X, int Y, short Point)

## static void cmpDrawGauge(int X, int Y, uint Z, uint BaseCol, datUnitWork_t pStock, byte Type, uint OtNo, [Optional] GameObject now, [Optional] GameObject max, [Optional] Image bar, [Optional] GameObject grey, [Optional] Image Gbar)

## static void cmpDrawHpMp(int X, int Y, uint[] pBaseCol, int Style, datUnitWork_t pStock)
Renders the HP and MP bars

## static void cmpDrawModelBadStatus(int X, int Y, uint[] pBaseCol, datUnitWork_t pStock)

## static void cmpDrawPlayerRaceFlash(int X, int Y, sbyte RaceID, int Rate)

## static void cmpDrawStatusPanel(int X, int Y, uint[] pBaseCol, int Style, datUnitWork_t pStock)

## static void cmpDrawParamGauge(int X, int Y, uint[] pBaseCol, int StepY, sbyte Pos, sbyte ParamOfs, sbyte FlashMode, datUnitWork_t pStock, GameObject stsObj)

## static void cmpDrawParamPanel(int X, int Y, uint[] pBaseCol, sbyte[] pParamOfs, datUnitWork_t pStock, sbyte CursorPos, sbyte CursorMode, sbyte FlashMode)

## static void cmpDrawAisyoHelp(int X, int Y, uint[] pBaseCol, int Style, datUnitWork_t pStock)

## static void cmpDrawAisyoPanel(int X, int Y, uint[] pBaseCol)

## static void cmpDrawSkillEffect(int X, int Y, sbyte Index)

## static void cmpDrawSkill(int X, int Y, uint[] pBaseCol, datUnitWork_t pStock, rstSkillInfo_t pSkillInfo, sbyte CursorPos, sbyte CursorMode, uint NextSkillColor, sbyte DrawMode, uint Style)
Renders the skill names in the Status menu
- pStock: Demon viewed
- pSkillInfo: Upcoming skills

## static void cmpDrawStatusCom(datUnitWork_t pStock, sbyte Style, sbyte FlashMode, sbyte SkillMode)

## static void cmpDrawStatusComEx(datUnitWork_t pStock, byte Alpha, sbyte CursorPos, sbyte CursorMode, sbyte[] pParamOfs, short SkillLevOfs, uint NextSkillColor, sbyte Style, sbyte FlashMode, sbyte SkillMode)

## static void cmpCalcTargetDevil(datUnitWork_t pStock, datUnitWork_t pWork)

## static void cmpUpdateStatusTimer()

## static void cmpDrawStatusComEx2(datUnitWork_t pStock, int X, int Y, byte Alpha, sbyte CursorPos, sbyte CursorMode, sbyte[] pParamOfs, short SkillLevOfs, uint NextSkillColor, sbyte Style, sbyte FlashMode, sbyte SkillMode, sbyte modeldraw)