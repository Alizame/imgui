project (Dear_ImGui)

set (imgui_headers imconfig.h imgui.h imgui_internal.h imstb_rectpack.h imstb_textedit.h imstb_truetype.h)
set (imgui_sources imgui.cpp imgui_demo.cpp imgui_draw.cpp imgui_widgets.cpp)

add_library(ImGui SHARED ${imgui_sources} ${imgui_headers})

cotire(ImGui)
