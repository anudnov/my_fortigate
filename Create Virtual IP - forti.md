```
config firewall vip
```
```
edit name 
set extip 8.8.8.8
set extintf "any"
set mappedip 10.10.10.2
next
edit name
set extip 8.8.4.4
set extintf "any"
set mappedip 10.10.10.3
next
```
```
end
```
