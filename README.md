# mechredline
Free and Open source PDF editor with a focus on redlining isometric piping drawings and other mechanical drawings like P&IDs.

Tools include
- Dimensioning callouts (not to scale) that can be skewed to the isometric plane
- a built-in construction calculator for imperial dimensions integrated with dimensions
- Free drawing, orthometric drawing, and isometric drawing
- lines, arrows, double sided arrows, curved lines, polylines
- shapes with border, fill, and styling options
- white-out tools
- opacity options for all tools
- library of pipe fittings that can be skewed to the isometric plane
- weld symbols
- BOM tables
- BOM callouts
- Drawing border and title bar for new drawings
- Select from various scratch-paper templates for new drawings
- Ability to add and style photos
- Automatic username/timestamp/logo placement (optional)
- No watermarks

Considerations
- All markups are saved as vector graphics and original text will still be searchable in final product.
- New markups are also text searchable.
- Can be integrated with the QCDATABASE.AI cloud platform if API key is saved to the `QCDATABASE_API_KEY` in your environment variables.
  - MechRedline will only have access to tenants and projects that your user account has access to.
  - Changes are made locally and redlines must be "pushed" as new drawing versions.
