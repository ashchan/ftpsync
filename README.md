FtpSync is a simple Ruby class to sync local directory to a remote ftp directory, or copy directories on remote server.

Usage
===========

	# ftp = FtpSync.new('ftp.site.com', 'user', 'password')
	# ftp.sync('/Users/james/Desktop/test_ftp', '/home/james/Sites')
	# ftp.copy_folder('folder1/pic', 'folder2/')
	
Note
===========

FtpSync doesn't work for FTP server on Windows. Sorry Windows guys. I don't have a chance to test running it on Windows to sync to ftp server on *nix, either.

It's extracted from my personal project, use it at your own risk.
