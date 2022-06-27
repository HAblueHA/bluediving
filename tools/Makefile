all: atshell attest bdaddr hcidump-crash hstest l2cap-packet l2cap_headersize_overflow rfcomm_shell

atshell: atshell.c
	echo -en "\n<<< Compiling atshell\n"
	gcc atshell.c -o atshell -lbluetooth -lreadline -lncurses 

attest: attest.c
	echo -en "\n<<< Compiling attest\n"
	gcc attest.c -o attest -lbluetooth

bdaddr: bdaddr.c
	echo -en "\n<<< Compiling bdaddr\n"
	gcc bdaddr.c -o bdaddr -lbluetooth

hcidump-crash: hcidump-crash.c
	echo -en "\n<<< Compiling hcidump-crash\n"
	gcc hcidump-crash.c -o hcidump-crash -lbluetooth 

hstest: hstest.c
	echo -en "\n<<< Compiling hstest\n"
	gcc hstest.c -o hstest -lbluetooth

l2cap-packet: l2cap-packet.c
	echo -en "\n<<< Compiling l2cap-packet\n"
	gcc l2cap-packet.c -o l2cap-packet -lbluetooth

l2cap_headersize_overflow: l2cap_headersize_overflow.c
	echo -en "\n<<< Compiling l2cap_headersize_overflow\n"
	gcc l2cap_headersize_overflow.c -o l2cap_headersize_overflow -lbluetooth

rfcomm_shell: rfcomm_shell.c
	echo -en "\n<<< Compiling rfcomm_shell\n"
	gcc rfcomm_shell.c -o rfcomm_shell -lbluetooth -lreadline -lncurses

clean:
	rm -f atshell attest bdaddr hcidump-crash hstest l2cap-packet l2cap_headersize_overflow rfcomm_shell


