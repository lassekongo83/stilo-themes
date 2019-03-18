gtk2_dir = join_paths(theme_dir, 'gtk-2.0')

# static theme files to copy
gtk2_theme_data_sources = [
  'gtkrc',
  'buttons.rc',
  'caja.rc',
  'check-radio.rc',
  'chromium.rc',
  'panel.rc',
  'pluma.rc',
  'thunar.rc',
]

gtk2_asset_dir = join_paths(gtk2_dir, 'assets')

# static asset files to copy
gtk2_asset_data_sources = [
  'assets/btn.png',
  'assets/btn-hover.png',
  'assets/btn-insensitive.png',
  'assets/btn-active.png',
  'assets/btn-active-hover.png',
  'assets/radio-unchecked.png',
  'assets/checkbox-unchecked-insensitive.png',
  'assets/radio-unchecked-hover.png',
  'assets/base-color.png',
  'assets/checkbox-checked-hover.png',
  'assets/checkbox-checked-insensitive.png',
  'assets/checkbox-checked.png',
  'assets/resize-grip.png',
  'assets/radio-checked-insensitive.png',
  'assets/radio-checked-hover.png',
  'assets/selected-color.png',
  'assets/checkbox-unchecked.png',
  'assets/checkbox-unchecked-hover.png',
  'assets/handle.png',
  'assets/radio-checked.png',
  'assets/radio-unchecked-insensitive.png',
  'assets/null.png',
]

# Install theme files
install_data(gtk2_theme_data_sources, install_dir: gtk2_dir)

# Install asset files
install_data(gtk2_asset_data_sources, install_dir: gtk2_asset_dir)
