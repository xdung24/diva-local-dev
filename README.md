
# Hướng dẫn

Sử dụng phpmyadmin để vào mysql database

## Tạo network divadev nếu chưa tạo

```bash
docker network create vidivadev
```

## Sửa config để trong domain vào máy local

- Vào Setting-Network, lấy IP address trong phần status  
- Vào file dnsmasq/dnsmasq.conf sửa IP 10.0.1.151 thành IP của máy mình
- Ở Setting-Network, vào Advanced - DNS - DNS Server, thêm IP 127.0.0.1 vào 

## Chạy services 

```bash
make
```
