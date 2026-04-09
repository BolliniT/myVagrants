mk_vsa:
Presuppone utilizzo **vsphere provider**.\\
Scelgo di passare da variabili ambiente: export VAGRANT_VMNAME=vm_name" e forma ENV['vm_name'] perchè possa utilizzarlo in Bash script con ciclo loop reiterato su "vm_name".\\
Esempio funzionante su vcbc. Da risorsa host/cluster: _compute_resource_name_ in vCenter _host_ prende il _template_name_ che clona in ENV['VAGRANT_VMNAME'].\\
Ci sarà da aggiornare il nome della conn nmcli\\
