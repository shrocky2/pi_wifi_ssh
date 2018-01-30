# pi_wifi_ssh
# code needed to setup wifi and ssh


# --------------------------------The Following is Wifi code--------------------------
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev

update_config=1

network={
        ssid="WIFI_NETWORK NAME_GOES_HERE"
        psk="WIFI_PASSWORD_GOES_HERE"
        proto=RSN
        key_mgmt=WPA-PSK
        pairwise=CCMP
        auth_alg=OPEN
}
