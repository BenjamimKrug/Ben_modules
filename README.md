# Ben_modules
My personal symbols, footprints and 3d models library for KiCad EDA. Some of the symbols and footprints I got either from porting the diy_modules library for Eagle EDA, which I was using for quite a while before changin to KiCad and some others I got from SnapEDA, the rest I made them myself. The 3D models I mostly got from GrabCad. I know most people also create they're own symbols and footprints instead of relying on other people's libraries, but I just wanted to share my own, since I think it's very complete for most makers and even professionals that use KiCad.

# Installation process
1. Clone the repository. 
2. go into KiCad and add the relative path to the library in the paths configuration:

<img src="/images/preferences menu paths.png" alt="preferences paths">

<img src="/images/paths menu add item.png" alt="add item to paths">

<img src="/images/paths menu unfilled.png" alt="unfilled path">

3. then fill the new field with the name being 'BEN_MODULES' and then set the path to the folder where you cloned the repository, in my case I put it in the Documents folder on Windows
<img src="/images/paths menu filled.png" alt="filled path">

4. With the path configured, add the symbol library on Preferences->Manage Symbol Libraries with the name Ben_modules:

<img src="/images/preferences menu symbols.png" alt="preferences symbols">

<img src="/images/symbols library add item.png" alt="add item to symbols library">

<img src="/images/symbols library unfilled.png" alt="unfilled symbols library">

5. then fill the new field with the name being 'Ben_modules' and then set the path to the symbols file using the relative path that you set before, filling the path with '${BEN_MODULES}\symbols\Ben_modules.kicad_sym', as seen below:

<img src="/images/symbols library filled.png" alt="filled symbols library">



6. then do the same with the Footprint library

<img src="/images/preferences menu footprint.png" alt="preferences footprint">

<img src="/images/footprints library add item.png" alt="add item to footprints library">

<img src="/images/footprints library unfilled.png" alt="unfilled footprints library">

7. then fill the new field with the name being 'Ben_modules' and then set the path to the symbols file using the relative path that you set before, filling the path with '${BEN_MODULES}/footprints/Ben_modules.pretty', as seen below:

<img src="/images/footprints library filled.png" alt="filled symbols library">

From that point on everything should be correctly configured and ready to use. In theory KiCad will inform you if it doesn't manage to find the files, so it should be simple to fix if any problem happens. If there is any issue please open an issue on the issues tab of the repository so that I can fix it the fastest I can. 