# Control by Ouroboros — shared listing copy (DRAFT)
Name: Control by Ouroboros
Tagline: AI TAKE THE WHEEL — let your AI assistant see and drive your PC, safely.
Short (≤100 chars): Desktop control MCP: your AI sees, clicks and types on your PC, with consent and hard safety blocks.
Long:
Control by Ouroboros is a local MCP server that lets Claude, ChatGPT, Cursor, VS Code and other MCP clients operate your computer: read the UI tree and window text, find controls, click, type, scroll, drag, switch windows and launch apps. It asks before taking over and you take control back instantly by grabbing the mouse. Built-in safety: payment screens, card numbers/CVVs, password and sign-in fields, and destructive terminal commands are blocked or held; deletes need explicit confirmation. Screen content is treated as untrusted.
Early release. Windows only. $7.50/month or $75/year per PC (15% off for 10+ PCs), 7-day free trial. Billing only on ouroborosapps.com.
Category: Productivity / Automation / Computer use
Tags: mcp, desktop-control, computer-use, automation, accessibility, ui-automation, windows
Version: 12.3.5 (early release, one-click Windows installer)
Publisher: Ouroboros Apps LLC
Website: https://ouroborosapps.com/control
Docs: https://ouroborosapps.com/docs/control
Privacy: https://ouroborosapps.com/control-privacy
Terms: https://ouroborosapps.com/control-terms
Support: https://ouroborosapps.com/support (ouroborosplugins@gmail.com)
Install/download URL: https://ouroborosapps.com/downloads/control/Control-Setup.exe

Tools (36, from v12.0.5 manifest; read-only = R, acts = A):
R screenshot, get_screen_size, list_windows, get_ui_tree, find_elements, read_text, screen_diff, wait, wait_for, qa_layout, whoami, control_status, look, vision_status, hello
A mouse_move, click, double_click, right_click, drag, scroll, batch, type_text, key_press, hotkey, focus_window, click_element, set_value, switch_window, open_path, launch_app, new_tab, confirm_delete, take_control, pass_control, release_control, release_all_keys

Example prompts:
1. "Open Notepad and type a shopping list for tacos."
2. "Find the Settings window and tell me what display scale is set."
3. "In the open browser, go to my calendar tab and read me today's events."
