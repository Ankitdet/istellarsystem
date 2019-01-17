# istellarsystem

 Application name : IStellarSystem
 StandAloneApplication : IStellarSystem.jar
 
--------------------------------------------------------------------
 Requirements
--------------------------------------------------------------------
 	- JRE 8 or above
 	- Make sure you have port 8085 free
 
---------------------------------------------------------------------
 Steps to Start 
---------------------------------------------------------------------
 
 - Copy & Paste IStellarSystem.jar
 - Open cmd.exe in Windows
 - Goto copied path
 - execute command : java -jar IStellarSystem.jar 
 - Open browser and url localhost:8085
 
-------------------------------------------------------------------
 Technology used
-------------------------------------------------------------------
 - SpringBoot and Spring framework
 - Derby DB
 - Hibernate 
 - JAX-RS 
 - Server : Apache tomcat server 8(In build tomcat)
 
-------------------------------------------------------------------------------------- 	
 planet.csv (must exist)
-------------------------------------------------------------------------------------- 	
 	   #Node,Name
		A,Earth
		B,Moon
		C,Jupiter
		D,Venus
		E,Mars
		F,Saturn
		G,Uranus
		H,Pluto
		I,Neptune
		J,Mercury
		K,Alpha Centauri
		L,Luhman 16
		M,Epsilon Eridani
		N,Groombridge 34
		O,Epsilon Indi
		P,Tau Ceti
		Q,Kapteyn's star
		R,Gliese 687
		S,Gliese 674
		T,Gliese 876#
		U,Gliese 832
		V,Fomalhaut
		W,Virginis
		X,HD 102365
		Y,Gliese 176
		Z,Gliese 436
		A',Pollux
		B',Gliese 86
		C',HIP 57050
		D',Piscium
		E',GJ 1214
		F',Upsilon Andromedae
		G',Gamma Cephei
		H',HD 176051
		I',Gliese 317
		J',HD 38858
		K',Ursae Majoris
 		
-------------------------------------------------------------------------------------- 	
traffic.csv (must exist)
-------------------------------------------------------------------------------------- 	
		#Route Id,Planet Origin,Planet Destination,Traffic Delay (Light Years)
		1,z,B,0.30
		2,A,C,0.90
		3,A,D,0.10
		4,B,H,0.20
		5,B,E,1.30
		6,C,F,0.30
		7,D,L,0.00
		8,D,M,0.20
		9,H,G,3.10
		10,E,I,6.10
		11,F,J,2.40
		12,F,K,0.30
		13,G,Z,4.00
		14,I,Z,3.70
		15,I,J,2.90
		16,L,T,9.80
		17,T,N,8.80
		18,T,S,13.40
		19,S,O,6.00
		20,O,U,3.50
		21,J,R,5.40
		22,R,P,1.90
		23,R,L',0.70
		24,Z,Y,3.20
		25,Y,Q,20.30
		26,Q,X,10.40
		27,L',X,8.10
		28,X,K',0.70
		29,P,U,8.40
		30,U,K',12.30
		31,U,J',2.50
		32,J',V,3.00
		33,K',V,7.20
		34,J',I',13.40
		35,Y,A',17.00
		36,A',B',7.20
		37,B',C',21.30
		38,K',W,16.00
		39,W,C',4.70
		40,W,E',33.90
		41,C',D',30.10
		42,E',E',7.60
		43,E',F',34.20
		44,F',G',2.40
		45,G',H',1.10

-----------------------------------------------------------------------------------------
vertex.csv (must exist)
-----------------------------------------------------------------------------------------
		#Route Id,Planet Origin,Planet Destination,Distance(Light Years)
		1,A,B,0.44
		2,A,C,1.89
		3,A,D,0.10
		4,B,H,2.44
		5,B,E,3.45
		6,C,F,0.49
		7,D,L,2.34
		8,D,M,2.61
		9,H,G,3.71
		10,E,I,8.09
		11,F,J,5.46
		12,F,K,3.67
		13,G,Z,5.25
		14,I,Z,13.97
		15,I,J,14.78
		16,L,T,15.23
		17,T,N,10.43
		18,T,S,14.22
		19,S,O,6.02
		20,O,U,5.26
		21,J,R,12.34
		22,R,P,10.10
		23,R,L',9.95
		24,Z,Y,18.91
		25,Y,Q,22.04
		26,Q,X,10.51
		27,L',X,23.61
		28,X,K',19.94
		29,P,U,9.31
		30,U,K',21.23
		31,U,J',25.96
		32,J',V,3.16
		33,K',V,20.42
		34,J',I',17.10
		35,Y,A',19.52
		36,A',B',31.56
		37,B',C',23.13
		38,K',W,28.89
		39,W,C',10.64
		40,W,E',36.19
		41,C',D',36.48
		42,E',E',41.26
		43,E',F',42.07
		44,F',G',17.63
		45,G',H',40.48
		 
---------------------------------------------------------------------------------------------
Inside app
---------------------------------------------------------------------------------------------

Menu display 
------------ 

	- Shortest Path -> Home page of application 
	- Planets -> View,Edit,Delete planets details
	- Routes -> View,Edit,Delete Routes details
	- Traffics -> View,Edit,Delete Traffic details
	- Add Planet -> Add new planet in Memory 
	- Add Route -> Add new route from one planet to next planet
	- Add Traffic -> Add traffic/time delay between two planets 
 
