# desta-api
-------------Render

syntax = render

color(int r, int g, int b, int a)

line(int x1, int y1, int x2, int y2)

filled_rect(int x1, int y1, int x2, int y2)

rect(int x1, int y1, int x2, int y2)

circle(int x,int y, int sRadius, int radius)

screenx()

screeny()

create_font(string name, int w, int h, int blur)

setup_font(font)

color_text(int r, int g ,int b, int a)

text(string name, int x, int y)

cursor_pos()

ClanTag(string tag)




-----------EngineClient

syntax = engine

ExecuteClientCmd(string command)

LocalPlayer()

IsInGame()

IsAlive()

Maxclients()
