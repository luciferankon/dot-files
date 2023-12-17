globinclude kitty.d/**/*.conf
term xterm-256color
shell_integration enabled
allow_hyperlinks yes

tab_bar_style powerline

window_border_width 0.5pt
window_resize_step_cells 2
window_resize_step_lines 2
initial_window_width 640
initial_window_height 400
draw_minimal_borders yes
inactive_text_alpha 0.7
hide_window_decorations no
macos_titlebar_color background
macos_thicken_font 0.75
active_border_color none
# default layout is vertical splits only
enabled_layouts splits
enable_audio_bell no


font_family FiraCode Nerd Font Mono Retina
font_size 16.0

# Dark One Nuanced by ariasuni, https://store.kde.org/p/1225908
# Imported from KDE .colorscheme format by thematdev, https://thematdev.org
# For migrating your schemes from Konsole format see
# https://git.thematdev.org/thematdev/konsole-scheme-migration
# importing Background
background #282c34
# importing BackgroundFaint
# importing BackgroundIntense
# importing Color0
color0 #3f4451
# importing Color0Faint
color16 #282c34
# importing Color0Intense
color8 #4f5666
# importing Color1
color1 #e06c75
# importing Color1Faint
color17 #c25d66
# importing Color1Intense
color9 #ff7b86
# importing Color2
color2 #98c379
# importing Color2Faint
color18 #82a566
# importing Color2Intense
color10 #b1e18b
# importing Color3
color3 #d19a66
# importing Color3Faint
color19 #b38257
# importing Color3Intense
color11 #efb074
# importing Color4
color4 #61afef
# importing Color4Faint
color20 #5499d1
# importing Color4Intense
color12 #67cdff
# importing Color5
color5 #c678dd
# importing Color5Faint
color21 #a966bd
# importing Color5Intense
color13 #e48bff
# importing Color6
color6 #56b6c2
# importing Color6Faint
color22 #44919a
# importing Color6Intense
color14 #63d4e0
# importing Color7
color7 #e6e6e6
# importing Color7Faint
color23 #c8c8c8
# importing Color7Intense
color15 #ffffff
# importing Foreground
foreground #abb2bf
# importing ForegroundFaint
# importing ForegroundIntense
# importing General



# clear the terminal screen
map cmd+k combine : clear_terminal scrollback active : send_text normal,application \x0c
# jump to beginning and end of word
map alt+left send_text all \x1b\x62
map alt+right send_text all \x1b\x66
# jump to beginning and end of line
map cmd+left send_text all \x01
map cmd+right send_text all \x05
# Map cmd + <num> to corresponding tabs
map cmd+1 goto_tab 1
map cmd+2 goto_tab 2
map cmd+3 goto_tab 3
map cmd+4 goto_tab 4
map cmd+5 goto_tab 5
map cmd+6 goto_tab 6
map cmd+7 goto_tab 7
map cmd+8 goto_tab 8
map cmd+9 goto_tab 9
# changing font sizes
map cmd+equal change_font_size all +2.0
map cmd+minus change_font_size all -2.0
map cmd+0 change_font_size all 0
map cmd+c copy_to_clipboard
map cmd+v paste_from_clipboard



map alt+1 goto_tab 1
map alt+2 goto_tab 2
map alt+3 goto_tab 3
map alt+4 goto_tab 4
map alt+5 goto_tab 5
map alt+6 goto_tab 6
map alt+7 goto_tab 7
map alt+8 goto_tab 8
map alt+9 goto_tab 9
map alt+0 goto_tab 0
# open new tab with cmd+t
map cmd+t new_tab_with_cwd
# switch between next and previous splits
map cmd+] next_window
map cmd+[ previous_window



# open new split (window) with cmd+d retaining the cwd
map cmd+w close_window
map cmd+shif+n new_os_window
map cmd+d launch --location=hsplit --cwd=current
map cmd+shift+d launch --location=vsplit --cwd=current




## Tab bar

tab_bar_edge bottom
tab_bar_align left
tab_bar_style custom
tab_bar_min_tabs 1
tab_activity_symbol none
bell_on_tab no
tab_separator ""
tab_bar_margin_width 0.0
tab_bar_margin_height 0.0 0.0
tab_title_template "{f'{title[:30]}…' if title.rindex(title[-1]) + 1 > 30 else (title.center(6) if (title.rindex(title[-1]) + 1) % 2 == 0 else title.center(5))}"
active_tab_font_style   bold
