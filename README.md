# configurations

0.
	 - git
	 	 - initalizing...
		git init
		git con
		git remote add origin "https//:<git-key>#github.com/<user>/<etc>..."

		 - pushing to repo
		git add . 
		git commit -m (this means [m]essage) "<message>"
		git push -u origin <branch>
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

		https://github.com/equalsraf/neovim-qt/issues/327
		 - Being able to Copy and Paste; There is a file within C:\Program Files\neovim\share\runtime that is called mswin.vim that allows windows commands within vim
		 - you can run cmdline commands from vim but it is very restrictive and linux like compared to native windows command execution experience. 
		 ex. :echo $VIMRUNTIME
			 - this command displays info that is only created when nvim is initalized!

		###yothisiscool.vim is mswin.vim
