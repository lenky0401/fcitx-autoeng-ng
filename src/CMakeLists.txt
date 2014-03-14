set(FCITX_AUTOENG_SOURCES
  iniparser/dictionary.c
  iniparser/iniparser.c
  cfgrw.c
  AutoEng.c)
fcitx_add_addon_full(autoeng-ng DESC
  SOURCES ${FCITX_AUTOENG_SOURCES}
  HEADERS AutoEng.h)
