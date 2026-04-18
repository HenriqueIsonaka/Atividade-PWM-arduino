Commit 2.1

Objetivo do teste:fazer com que o LED ficasse aceso na cor laranja.

Resultado: o LED ficou aceso na cor laranja por meio da regulação de intensidade dos LEDs vermelho e verde, sendo o verde um pouco mais fraco, via PWM.

<img width="848" height="478" alt="Design sem nome" src="https://github.com/user-attachments/assets/a657c168-77aa-4af7-b21f-9dab126d1e5e" />

Commit 2.2

Objetivo do teste: fazer com que o LED ficasse piscasse por 1 segundo na cor laranja.

Resultado: o LED ficou piscando na cor laranja por meio da regulação de intensidade dos LEDs vermelho e verde, sendo o verde um pouco mais fraco, e da alteração do duty cicle do PWM no looping a cada 1 segundo.

<img width="426" height="240" alt="GIF LED laranja piscante" src="https://github.com/user-attachments/assets/154529f4-3ff6-4642-8c9a-425bf43450c8" />

Commit 3

Objetivo do teste: fazer os motores do carrinho girarem.

Resultado: os motores giraram ao ligar a bateria ao VCC, ENA e ENB.

<img width="426" height="240" alt="GIF motor rodando" src="https://github.com/user-attachments/assets/0c47b647-3d82-4397-b24a-8442ebe84c66" />

Commit 4.1

Objetivo do teste: fazer um dos motores variar velocidade.

Resultado: o motor A variou velocidade, alternando entre 100% de velocidade, 25% de velocidade e parados, por meio da mudança do duty cycle do PWM do TPM1 estabelecida no looping do código. Enquanto isso, o motor B manteve-se com velocidade constante.

<img width="426" height="240" alt="GIF uma roda alternando velocidade" src="https://github.com/user-attachments/assets/82d3f018-ff31-4882-9afc-da41feee852f" />

Commit 4.2

Objetivo do teste: fazer os dois motores variarem velocidade de forma sincronizada.

Resultado: os motores variaram suas velocidades de forma sincronizada, alternando entre 100% de velocidade, 25% de velocidade e parados, por meio da mudança do duty cycle do PWM estabelecida no looping do código.

<img width="426" height="240" alt="GIF rodas girando em sincronia" src="https://github.com/user-attachments/assets/9b4884b8-8df0-49e0-8e2f-503b26841291" />
