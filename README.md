# 🌐 Portfolio Réseau & Systèmes - Projets Cisco Packet Tracer

Bienvenue sur mon dépôt dédié à mes exercices et projets pratiques de mise en réseau réalisés dans le cadre de ma reconversion professionnelle en tant qu'**Administrateur Systèmes et Réseaux**. 

Ce dépôt regroupe plusieurs architectures réseaux simulées sous **Cisco Packet Tracer**, démontrant ma maîtrise des concepts fondamentaux et avancés du routage, de la commutation et du subnetting.

---

## 🚀 Compétences Démontrées

* **Routage Statique :** Configuration de routes statiques et de routes par défaut pour interconnecter des sous-réseaux distants.
* **Adressage & Subnetting IPv4 :** Découpage de réseaux avec masques adaptés (`/24`, `/27`, `/28`) et gestion des liaisons point-à-point en `/30`.
* **Segmentation VLAN :** Implémentation de VLANs (Clients, Gestion-IT, Serveurs) pour sécuriser et compartimenter le trafic de niveau 2.
* **Inter-VLAN Routing :** Configuration du routage inter-VLAN (technique Router-on-a-Stick).
* **Services Réseau :** Simulation de serveurs DHCP et DNS au sein d'une topologie d'entreprise.
* **Dépannage & Vérification :** Utilisation des commandes de diagnostic (`ping`, `traceroute`, `show ip route`).

---

## 📂 Aperçu des Projets / Topologies

### 1. Topologie Multi-Routeurs et Routage Statique Avancé
* **Description :** Architecture interconnectant plusieurs routeurs via des liaisons WAN point-à-point (`/30`) et des réseaux locaux distincts. Mise en place d'un routage statique complet pour assurer la joabilité de bout en bout entre tous les départements.
* **Fichiers associés :** `multi_router_routing.pkt` *(Remplacez par le nom réel de votre fichier)*
* **Points techniques clés :** 
  * Gestion de tables de routage statiques complexes.
  * Optimisation des chemins réseau à travers des passerelles multiples.

### 2. Segmentation par VLANs et Routage Inter-VLAN (Router-on-a-Stick)
* **Description :** Conception d'un réseau d'entreprise segmenté en plusieurs VLANs logiques :
  * **VLAN 10 (Clients) :** `192.168.10.0/24
  * **VLAN 20 (Gestion - IT) :** `192.168.20.0/27
  * **VLAN 30 (Serveurs DNS/DHCP) :** `192.168.30.0/28
* **Points techniques clés :** Configuration des ports trunk/access sur les switchs et encapsulation 802.1Q sur le routeur.

### 3. Topologie de Base et Apprentissage Fondamental
* **Description :** Premiers pas sur la configuration d'interfaces, attribution d'adresses IP aux équipements finaux (PC) et validation de la connectivité locale.
* **Fichiers associés :** `basic_routing_switch.pkt` *(Remplacez par le nom réel)*

---

## 🛠️ Outils & Technologies Utilisés

* **Logiciel de simulation :** Cisco Packet Tracer
* **Matériel émulé :** Routeurs Cisco (séries 1900/2900), Switchs Catalyst (2960), Terminaux (PC, Serveurs).
* **Protocoles :** IPv4, TCP/IP, ICMP, ARP, 802.1Q (Trunking).

---

## 📈 À Propos de ma Reconversion

En reconversion vers les métiers de l'infrastructure et des réseaux, je mets un point d'honneur à valider mes compétences théoriques par de la **mise en pratique rigoureuse**. Ce dépôt témoigne de ma capacité à concevoir, configurer et dépanner des architectures réseaux de zéro.

* 💼 **Recherche :** À l'écoute d'opportunités en tant qu'**Administrateur Systèmes et Réseaux** (alternance ou premier poste).
* 📬 **Contact :** https://www.linkedin.com/in/laetitia-dhont/ | laetitiadhont75@gmail.com

---
⭐ *N'hésitez pas à parcourir les fichiers `.pkt` inclus dans ce dépôt pour explorer les configurations en détail !*
