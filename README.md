* Create a user `gtk`. As this user:
 	* Build Gtk-OSX: http://sourceforge.net/apps/trac/gtk-osx/wiki/Build
		* We need the package meta-gtk-osx-core
		* Also need ige-mac-integration at least version 0.9.8, previous versions don't like BasiliskIIGUI's menus
		* Use a `.jhbuildrc.custom` containing `setup_sdk(target="10.4", sdk_version="10.4u", architectures=["i386"])`
	* Install ige-mac-bundler: http://sourceforge.net/apps/trac/gtk-osx/wiki/Bundle
		* It has a bug, so use my repo: https://github.com/vasi/ige-mac-bundler

