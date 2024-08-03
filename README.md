ssh-keygen -t rsa -b 4096 -C yourname@protonmail.com
	   
	   ssh -v administrator@192.168.1.246 -i "d:\id_rsa"
	 ssh -v administrator@localhost -i "d:\id_rsa"
	 
	 authorized_keys in .ssh or administrators_authorized_keys in programdata 
	 put public key (on server)
	 
	 
	 if error permission - security - advanced - disable inheritance 
	 delete another user except administrators & system 
