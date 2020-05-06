$TTL    604800
@       IN      SOA     okd-services.authoritah.com. admin.authoritah.com. (
                  1     ; Serial
             604800     ; Refresh
              86400     ; Retry
            2419200     ; Expire
             604800     ; Negative Cache TTL
)

; name servers - NS records
    IN      NS      okd-services

; name servers - A records
okd-services.authoritah.com.          IN      A       192.168.1.210

; OpenShift Container Platform Cluster - A records
okd-bootstrap.lab.authoritah.com.        IN      A      192.168.1.200
okd-control-one.lab.authoritah.com.        IN      A      192.168.1.201
okd-control-two.lab.authoritah.com.         IN      A      192.168.1.202
okd-control-three.lab.authoritah.com.         IN      A      192.168.1.203
okd-compute-one.lab.authoritah.com.        IN      A      192.168.1.204
okd-compute-two.lab.authoritah.com.        IN      A      192.168.1.205

; OpenShift internal cluster IPs - A records
api.lab.authoritah.com.    IN    A    192.168.1.210
api-int.lab.authoritah.com.    IN    A    192.168.1.210
*.apps.lab.authoritah.com.    IN    A    192.168.1.210
etcd-0.lab.authoritah.com.    IN    A     192.168.1.201
etcd-1.lab.authoritah.com.    IN    A     192.168.1.202
etcd-2.lab.authoritah.com.    IN    A    192.168.1.203
console-openshift-console.apps.lab.authoritah.com.     IN     A     192.168.1.210
oauth-openshift.apps.lab.authoritah.com.     IN     A     192.168.1.210

; OpenShift internal cluster IPs - SRV records
_etcd-server-ssl._tcp.lab.authoritah.com.    86400     IN    SRV     0    10    2380    etcd-0.lab
_etcd-server-ssl._tcp.lab.authoritah.com.    86400     IN    SRV     0    10    2380    etcd-1.lab
_etcd-server-ssl._tcp.lab.authoritah.com.    86400     IN    SRV     0    10    2380    etcd-2.lab
