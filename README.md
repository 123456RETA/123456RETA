/*************/ 
/* SEMÁFORO */ 
/*************/ 



//** Definiciones **// 
int rojo=3; //definimos el valor del pin para el led rojo 
int amarillo=5; //definimos el valor del pin para el led amarillo 
int verde=8; //definimos el valor del pin para el led verde 


//** Programa **// 


void setup() { //declaraciones 
pinMode(verde,OUTPUT); //declaramos el pin verde como salida 
pinMode(amarillo,OUTPUT);//declaramos el pin amarillo como salida 
pinMode(rojo,OUTPUT); //declaramos el pin rojo como salida 
} 


void loop() { //bucle a repetir continuamente 
digitalWrite(verde,HIGH); //encendemos el led verde 
delay(15000); //esperamos 15 segundos 
digitalWrite(verde,LOW); //apagamos el led verde 
delay(250); //esperamos 0,250 segundos 


digitalWrite(amarillo,HIGH); //encendemos el led amarillo 
delay(3000); //esperamos 3 segundos 
digitalWrite(amarillo,LOW); //apagamos el led amarillo 
delay(250); //esperamos 0,250 segundos 


digitalWrite(rojo,HIGH); //encendemos el led rojo 
delay(15000); //esperamos 15 segundos 
digitalWrite(rojo,LOW); //apagamos el led rojo 
delay(250); //esperamos 0,250 segundos 
}
