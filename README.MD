https://medium.com/keycloak/apache-ds-ldap-as-user-federation-in-keycloak-5978838d53c0
https://hub.docker.com/r/openmicroscopy/apacheds




docker-compose -f keyalksdjf up


docker exec -it  [the open ldap instance] bash 

# get your ip address:
#   one way is to do this and get the local address of the form:
#      0230A8C0   ---> endianess is backwards ---> this is 192.168.48.2
#        
cat /proc/net/tcp   



open keycloak and use following in the ldap connection url - just use the correct IP from above
   ldap://192.168.48.2:10389

  USER DN:  uid=admin,ou=system
  PASSWORD: secret





# keycloakLDAPStandalone
# keycloakLDAPStandalone
# keycloakLDAPStandalone
