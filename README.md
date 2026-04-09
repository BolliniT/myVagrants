mk_vsa:
Presuppone utilizzo **vsphere provider**.
Scelgo di passare da variabili ambiente: export VAGRANT_VMNAME="nome scelto" e forma ENV['nome scelto'] per un futura aggiornameto in adozione ciclo loop. Questo consente di avviarne diverse.
Da risorsa host/cluster: _compute_resource_name_ in vCenter _host_ prende il _template_name_ che clona in ENV['VAGRANT_VMNAME'].
Ci sarà da aggiornare il nome della conn nmcli
