# Issue/PR Tracking
Follow Procedure layed out by .github templates

Titles must be descriptive

No Logs, No Help

# Contribution Guide
- Use Hard Tabs
- Avoid Hard Wrapping (recommended, not required)
- Don't Wrap Comments
- Block Levels must be indented
- Conatanst Must Be fully UPPERCASED
- One line statements can omit brackets
- All public and protected methods must be documented (private methods should be documented, but not required)
- If library interaction is handled entirely in a seperate package, name the package accordingly
- Avoid removal of public and protected methods or variables, deprecation suggested
- Mark inconsistent version handling
- Use global (consistent support for all versions) objects if possible

# Forking
To fork this repo you must (replace gradle with gradlew if you don't have gradle installed):

1. Fork
2. Run `gradle setupDecompWorkspace`
3. <TODO: handle IDE forking>