# -Rocket.Chat_ES_MarcosGabriel_MartinsRibeiro
Rocket.Chat Technical Test

TOKEN: sqQQaMdyFasuom3-doJL8koWZQvuXdjltQGjeaSs8VA

ID-USER: j49QmA8tadgXuvKf

Question 1 - 

curl -H "X-Auth-Token: sqQQaMdyFasuom3-doJL8koWZQvuXdjltQGjeaSs8VA" \
     -H "X-User-Id: Mj49QmA8tadgXuvKf" \
     -H "Content-type:application/json" \
     http://ec2-15-228-251-43.sa-east-1.compute.amazonaws.com:3000/api/v1/users.create \
     -d '{"name": "name", "email": "email@user.tld", "password": "anypassyouwant", "username": "uniqueusername"}'
     
Question 2 - 

curl -H "X-Auth-Token: sqQQaMdyFasuom3-doJL8koWZQvuXdjltQGjeaSs8VA" \
     -H "X-User-Id: Mj49QmA8tadgXuvKf" \
     -H "Content-type: application/json" \
     http://ec2-15-228-251-43.sa-east-1.compute.amazonaws.com:3000/api/v1/rooms.get
     
Question 3 -

curl -H "X-Auth-Token: sqQQaMdyFasuom3-doJL8koWZQvuXdjltQGjeaSs8VA" \
     -H "X-User-Id: Mj49QmA8tadgXuvKf" \
     http://ec2-15-228-251-43.sa-east-1.compute.amazonaws.com:3000/api/v1/roles.list
