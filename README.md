# Exercicio_em_Sala_1-Programa-BLINK

# Arduino feito no tinkercad
![Editing Components](https://github.com/user-attachments/assets/d9307937-88b4-49c1-bb30-952026e11157)


# Codígos
void setup() {
pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
digitalWrite(LED_BUILTIN, HIGH);
delay(1000); // espera por um segundo
digitalWrite(LED_BUILTIN, LOW);
delay(1000); // espera por um segundo
}
