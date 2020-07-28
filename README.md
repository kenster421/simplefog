# Allows manual drawing of fog of war
Lets you draw fog of war manually

# todo
- ~~Hide token/doors/other interactables under fog~~
- ~~Brush sizes~~
- ~~Brush/tool + - & .5~~
- ~~Handle canvas resize~~
- ~~Fog Color & Opacity~~
- ~~Box Shape~~
- ~~Circle Shape~~
- ~~Poly Shape~~
- ~~Undo~~
- ~~refactor mask layer to its own class to be reusable~~
- ~~Grid snap brush~~
- ~~Hex grid snap brush~~
- ~~Optimization~~
- ~~Blur~~
- ~~Mouse cursor tool indications~~
-- todo: hex grid
- ~~Allow cancel of current drawing via right click while dragging
-- implemented for shape tool, but ellipse / box not working
- Documentation
- Shift / ctrl shape tool modifiers
- ~~Blur filter should recalcuate pixel width to maintain consistency with zoom level~~
- Keybindings for changing brush size
- ~~Allow saving current settings as new default~~
- Visibility options
-- ~~Disable autoVis~~
-- ~~Visibility threshold~~
-- Reveal based on center of token
-- Reveal only if entire token visible
-- Reveal if any part of token is visible

# bugs
- sometimes hex grid tool stops drawing certain hexes
- ~~error when activating scene with no player token~~
- ~~create a light, use mask brush tool, blank journal entries will be created~~
- ~~preview shapes cannot be seen on full opacity black fog~~
- ~~Switching scenes dupes mouse listeners~~

# future features
- Opacity indactors on brush previews - red / green / grey for hide / show / 50% etc
- Brush Smoothing / Interpolation
- Image based fog import
- localizations
- sepia / monochrome filters
- Allow revealing core dynamic fog to the "explored" state, while retaining active line of sight fog as underlay