################## CROSSHAIR ##################
cl_crosshair_drawoutline "0"
cl_crosshair_dynamic_maxdist_splitratio "0.35"
cl_crosshair_dynamic_splitalpha_innermod "1"
cl_crosshair_dynamic_splitalpha_outermod "0.5"
cl_crosshair_dynamic_splitdist "7"
cl_crosshair_outlinethickness "1"
cl_crosshair_sniper_show_normal_inaccuracy "0"
cl_crosshair_sniper_width "1"
cl_crosshair_t "0"
cl_crosshairalpha "200"
cl_crosshaircolor "5"
cl_crosshaircolor_b "255"
cl_crosshaircolor_g "255"
cl_crosshaircolor_r "255"
cl_crosshairdot "0"
cl_crosshairgap "-2"
cl_crosshairgap_useweaponvalue "0"
cl_crosshairscale "4"
cl_crosshairsize "2"
cl_crosshairstyle "4"
cl_crosshairthickness "1"
cl_crosshairusealpha "1"
cl_fixedcrosshairgap "-4.5"
###############################################

################## VIEWMODEL ##################
cl_viewmodel_shift_left_amt "0.500000"
cl_viewmodel_shift_right_amt "0.250000"
viewmodel_fov "68"
viewmodel_offset_x "2"
viewmodel_offset_y "2"
viewmodel_offset_z "-2"
viewmodel_presetpos "0"
viewmodel_recoil "0"
cl_bob_lower_amt "5.000000"
cl_bobamt_lat "0.100000"
cl_bobamt_vert "0.100000"
cl_bobcycle "0.98"
###############################################

#################### RADAR ####################
cl_radar_square_with_scoreboard "0"
cl_radar_always_centered "0"
cl_radar_scale "0.3"
cl_hud_radar_scale "1.2"
cl_radar_rotate "1"
cl_radar_icon_scale_min "0.5"
###############################################

#################### BINDS ####################
//Boton para hablar(Con el mouse)
Bind "MOUSE5" "+voicerecord"

//Boton para ver el equipamiento
Bind "Q" "+showinven"

//Boton para soltar el C4(Se tiene que plantar con la tecla de Uso(Default:E))
Bind "5" "use weapon_knife; use weapon_c4; drop"

//Bind para abrir la consola (| o °)
Bind "\" "toggleconsole"

//Bind para ver el net graph al abrir el tabulador
Bind "TAB" "+scorenet"

//Binds para forrear
Bind "F1" "say El corchazo es inminente..."
Bind "F2" "say No se bancan comerse una balita del rey del barrio, hijos de puta"
Bind "F3" "say Oloko"
Bind "F4" "say Riko Tapi"
Bind "F5" "say La concha de tu madre pubero del orto volve a dust2 con tu p90"
Bind "F6" "say Counter Strike: Global Offensive -> click de derecho -> Desinstalar, PETE"
Bind "F7" "say No team ¯\_(ツ)_/¯"
###############################################

##################### HUB #####################
//Muestra la cantidad de jugadores vivos en vez de las fotos de perfil y la vida
cl_hud_playercount_showcount "1";

//Hub simple
cl_hud_healthammo_style "1";

//Opacidad del hub(Solido)
cl_hud_background_alpha "1";

//Color del hub(Default)
cl_hud_color "0"
###############################################

#################### AUDIO ####################
//Volumen
volume "0.70"

//El voice scale sirve para bajar el volumen de los demas
voice_scale "0.2"

//Desactiva el Audio 3D
snd_hwcompat "1"

//Sonido de 10 segundos restantes para el defuse
snd_tensecondwarning_volume "0.10"

//sonido en segundos plano(Cuando el juego esta minimizado)
snd_mute_losefocus "0"

//Desactiva todos los sonidos que no sirven, como la musica
snd_musicvolume "0.0"
snd_deathcamera_volume "0.0"
snd_mapobjective_volume "0.0"
snd_roundend_volume "0.0"
snd_roundstart_volume "0.0"
snd_menumusic_volume "0"
###############################################

################### CONFIG ####################
//Max mm Ping(80ms)
mm_dedicated_search_maxping "80"

//No selecciona el arma que agarras del suelo automaticamente
cl_autowepswitch "0"

//Indicador de enemigo en la mira
hud_showtargetid "1"

//Configura el net graph
net_graph 1
net_graphheight 9999
net_graphproportionalfont 0.1
net_graphpos 2

//Banda ancha(Ilimitada)
rate "786432"

//Rates
cl_cmdrate "128"
cl_updaterate "128"
cl_interp "0"
cl_interp_ratio "1"
cl_lagcompensation "1"

//Activar la consola
con_enable "1"

//Limite de fps(Sin limite)
fps_max 0
fps_max_menu 0
###############################################

################## FUNCTIONS ##################
//Net graph y tabulador
alias "+scorenet" "+showscores; net_graphheight 0"
alias "-scorenet" "-showscores; net_graphheight 9999"

//Mostrar equipamiento
alias "+showinven" "+cl_show_team_equipment"
alias "-showinven" "-cl_show_team_equipment"
###############################################

echo Listo Cumpa, ahrre que igual no vas a pegar una...
