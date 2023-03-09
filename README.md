# configurations

1. windows
	 - nvim/neovim 	
		[reference](https://github.com/neovim/neovim/wiki/Installing-Neovim)
		installation of nvim with the following command
		 - winget install Neovim.Neovim
		
		making nvim callable from cmd line
		 - edit system variables
		 - within the path variable (PATH, Path) add the location of nvim's bin folder
		 ex. C:\Program Files\neovim\bin
		 - remember to hit 'ok' when editing environment/env variables and to restart the cmd to refresh env variables

		configuring nvim
		 " Stupidly you have to make your own nvim directory and configuration file, always focus on tutorials and watch them fully to recognize this.
		 - go to AppData directory from your $HOME directory
		 ex of $HOME. $HOME = C:\Users\<Name>
			 - windows has the $HOME directory saved automatically
		 ex of going into Appdata. C:\Users\<Name>$ cd AppData
		 - Then go into local and ls, ls if you want to see all the folders that pull data from here.
		 ex. cd local
		 ex. ls
		 - finally, you HAVE to create an nvim folder, nvim-data is for data and plugins, it is stupid.
		 ex. mkdir nvim
		 - then you can put your 'init.vim' within it and configure.
		## you can use the init.vim provided from this repo.