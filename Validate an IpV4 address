import socket

def is_valid_ipv4(ip):
    try:
        # Attempt to create a socket connection with the given IP address
        socket.inet_pton(socket.AF_INET, ip)
        return True
    except socket.error:
        return False

# Input an IPv4 address to validate
ip_address = input("Enter an IPv4 address: ")

if is_valid_ipv4(ip_address):
    print(f"{ip_address} is a valid IPv4 address.")
else:
    print(f"{ip_address} is not a valid IPv4 address.")
