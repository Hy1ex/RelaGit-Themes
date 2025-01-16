dark-theme Elements with default values from "https://github.com/relagit/relagit/tree/main/packages/app/src/app.scss":
@mixin dark-theme {
	--font-primary: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu,
		Cantarell, 'Helvetica Neue', sans-serif;
	--font-mono: var(--settings-font-family, 'SF Mono', 'Fira Code', monospace);
	--color-contrast: var(--base-white);
	--color-primary: var(--dark-base-dark-grey);
	--color-secondary: var(--dark-base-grey);
	--color-link: var(--color-blue-500);
	--color-error: var(--color-red-500);
	--color-success: var(--color-green-500);
	--color-warning: var(--color-yellow-500);
	--status-added: var(--color-green-800);
	--status-modified: var(--color-yellow-800);
	--status-deleted: var(--color-red-800);
	--status-renamed: var(--color-violet-800);
	--status-untracked: var(--color-blue-800);
	--bg-primary: var(--dark-material-primary);
	--bg-secondary: var(--dark-material-secondary);
	--bg-tertiary: var(--dark-material-tertiary);
	--bg-quaternary: var(--dark-material-quaternary);
	--bg-quinary: var(--dark-material-quinary);
	--bg-senary: var(--dark-material-senary);
	--bg-material: var(--bg-tertiary);
	--bg-floating: var(--bg-secondary);
	--bg-tooltip: var(--dark-base-darker-grey);
	--bg-brand: var(--color-blue-500);
	--bg-hover: #{greyscale(color.adjust(illyrica.$color-blue-500, $alpha: -0.9))};
	--bg-active: #{(color.adjust(illyrica.$color-blue-500, $alpha: -0.7))};
	--bg-active-unfocused: #{greyscale(color.adjust(illyrica.$color-blue-500, $alpha: -0.7))};
	--bg-error: rgb(227 83 83 / 5%);
	--bg-error-solid: rgb(227 83 83 / 20%);
	--bg-success: rgb(82 228 82 / 5%);
	--bg-success-solid: rgb(82 228 82 / 20%);
	--bg-warning: rgb(236 197 118 / 5%);
	--bg-warning-solid: rgb(236 197 118 / 20%);
	--bg-diff-add: var(--bg-success);
	--bg-diff-add-solid: var(--bg-success-solid);
	--bg-diff-del: var(--bg-error);
	--bg-diff-del-solid: var(--bg-error-solid);
	--separator-primary: var(--dark-base-light-grey);
	--separator-secondary: var(--dark-base-lighter-grey);
}
Elements for light-theme is the same as dark-theme just different values

Styling:
#component {
    element-modifier: var;
    --element: var;
}

Example:
#app-container {
    --dark-material-primary: #282a36;
    --dark-material-secondary: #44475a;
    --dark-material-tertiary: #282a36;
    --dark-material-quaternary: #282a36;
    --dark-material-quinary: #44475a;
    --dark-material-senary: #ff5555;
    --dark-base-light-grey: rgb(16, 16, 20);
    --dark-base-lighter-grey: rgba(16, 16, 20, 0.4);
}

Elements:
https://github.com/relagit/relagit/tree/main/packages/app/src/app.scss
https://github.com/relagit/relagit/tree/main/packages/app/src/ui

Other Themes:
https://github.com/TheCommieAxolotl/relagit-themes
