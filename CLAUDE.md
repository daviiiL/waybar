# Waybar Configuration Guidelines

## Commands
- Launch waybar: `waybar` or `./waybar.sh`
- Restart waybar: `killall -q waybar && waybar`
- Test config syntax: `waybar -c config -s style.css`

## Style Guidelines
- Use CSS variables from `colors.css` for consistent theming
- Follow existing CSS naming conventions: `#module-name`
- Indent with 2 spaces in all files
- Keep JSON config clean and properly indented
- Shell scripts should use POSIX-compatible syntax when possible
- Document module dependencies in script headers

## Branch Information
- Main branch is for desktop configuration
- Use laptop branch for laptop-specific configurations
- All commit messages should clearly describe changes

## Module Development
- Custom modules should return valid JSON for waybar
- Script files should be executable (`chmod +x`)
- Keep module scripts simple and efficient
- Verify icon availability in your font before use