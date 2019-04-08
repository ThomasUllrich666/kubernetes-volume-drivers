FROM ubuntu:18.04
ADD ./smb /bin/smb
ADD ./install.sh /bin/install_smb_flexvol.sh
RUN chmod +x /bin/install_smb_flexvol.sh
RUN chmod +x /bin/smb

ENTRYPOINT ["/bin/install_smb_flexvol.sh"]

