## Auto HandBrake ##
Convert video files automatically by traversing directories.

## Usage ##
	Optional Flags:
		-h: Display this dialog
		-d: Enable Debugging.
		-T: Tidy flag. Toggle this to remove old movie file. Default is to leave old files in place, but put them in .TEMP folder.
	Required Flags:
		-D target_dir: Set the target directory (absolute path).
		-C target_files: Add a file extension to search for to convert.
		-F target_format_#: Select the format to encode in.
			Available Formats:
				[0] Universal
				[1] iPod
				[2] iPhone & iPod Touch
				[3] iPhone 4
				[4] iPad
				[5] AppleTV
				[6] AppleTV 2
				[7] Normal
				[8] High Profile
				[9] Classic
				[10] AppleTV Legacy
				[11] iPhone Legacy
				[12] iPod Legacy
