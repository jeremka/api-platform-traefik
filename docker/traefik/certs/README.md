# If it's the firt install of mkcert, run
mkcert -install
# Generate certificate for domain ".local" and their sub-domains
mkcert -cert-file certs/local-cert.pem -key-file certs/local-key.pem "*.local"
