
# Treafik installation
![Traefik installation](media/traefik_install.png)

# Metallb installation
![Metallb installation](media/metallb_install.png)

# Metallb config
![Metallb config](medida/metallb_config.png)

# Traekfik working
![Traefik_load_balancer](media/treafik_lb.png)

# Apply -f apps/
![Command result](media/apply_apps.png)

# App response from command line
![Respuestas desde URL](media/app_response.png)

MetalLB asigna 192.168.49.200 dentro de la red de Minikube. Como uso Windows con driver Docker, esa red no es accesible desde el host, por lo que utilicé minikube tunnel y apunté el hosts de Windows a 127.0.0.1.