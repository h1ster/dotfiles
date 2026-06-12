#define MOD Mod1Mask

static const char *term[]   = { "st", NULL };
static const char *dmenu[]  = { "dmenu_run", NULL };
static const char *quitwm[] = { "pkill", "Xorg", NULL };
static const char *scr_full[] = { "scrot", NULL };
static const char *scr_area[] = { "scrot", "-s", "-d", "1", NULL };

static struct key keys[] = {
    { MOD|ShiftMask, XK_Return, run, {.com = term} },
    { MOD,           XK_p,      run, {.com = dmenu} },

    { MOD|ShiftMask, XK_c,      win_kill,   {0} },
    { MOD,           XK_f,      win_fs,     {0} },
    { MOD,           XK_Tab,    win_next,   {0} },
    { MOD|ShiftMask, XK_q,      run, {.com = quitwm} },

    { MOD, XK_Print,          run, {.com = scr_full} },
    { MOD|ShiftMask, XK_Print, run, {.com = scr_area} },

    { MOD, XK_1, ws_go, {.i = 1} },
    { MOD, XK_2, ws_go, {.i = 2} },
    { MOD, XK_3, ws_go, {.i = 3} },
    { MOD, XK_4, ws_go, {.i = 4} },
    { MOD|ShiftMask, XK_1, win_to_ws, {.i = 1} },
    { MOD|ShiftMask, XK_2, win_to_ws, {.i = 2} },
    { MOD|ShiftMask, XK_3, win_to_ws, {.i = 3} },
    { MOD|ShiftMask, XK_4, win_to_ws, {.i = 4} },
};

