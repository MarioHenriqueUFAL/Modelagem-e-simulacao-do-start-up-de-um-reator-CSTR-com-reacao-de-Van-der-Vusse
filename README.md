# Modelagem-e-simulacao-do-start-up-de-um-reator-CSTR-com-reacao-de-Van-der-Vusse
Este repositório contém os projetos python que foram desenvolvidos por mim na disciplina de "Tópicos de Inteligência Artificial Aplicados à Engenharia Química"

O código deste projeto foi desenvolvido com o objetivo de modelar um reator CSTR operando com a reação de Van der Vusse e simular a partida do reator CSTR a partir
de condições iniciais pré-estabelecidas. A partir da simulação é possível avaliar o comportamento tempoeral das concentrações de reagentes e produtos e as temperaturas
da mistura reacional e do fluido refrigerante contido na camisa de resfriamento/aquecimento. Além disso, através da simulação podemos determinar o tempo que o sistema 
leva para atingir o estado estacionário (variáveis permanecem constantes com o tempo).

Primeiramente o reator é iniciado fornecendo-se os parâmetros físicos do reator, parâmetros termodinâmicos e parâmetros cinéticos da reação de Van der Vusse.
Os parâmetros são:

Volume do reator (Vr);
Densidade da corrente de reagente (ro_r);
Capacidade calorífica do reagente (cp_r);
Massa de fluido refrigerante (mc);
Capacidade calorífica do fluido refrigerante (cp_c);
Área da superfície de transferência de calor (Ar);
Coeficiente global de transferência de calor (U);
Parâmetros cinéticos da reação:
Fator pré-exponencial da reação 1 (k01);
Fator pré-exponencial da reação 2 (k02);
Fator pré-exponencial da reação 3 (k03);
Razão entre a energia de ativação da reação 1 e a constante dos gases R (E1_R);
Razão entre a energia de ativação da reação 2 e a constante dos gases R (E2_R);
Razão entre a energia de ativação da reação 3 e a constante dos gases R (E3_R).

Para a simulação da partida do reator são fornecidos os seguintes parâmetros:

Concentração inicial do reagente A na mistura reacional (Ca_inicial);
Concentração inicial do componente B na mistura reacional (Cb_inicial);
Temperatura inicial da mistura reacional (Tr_inicial);
Temperatura inicial do fluido refrigerante (Tc_inicial);
Temperatura da corrente de alimentação (mantido fixo) (Tr0);
Calor retirado ou fornecido pelo fluido refrigerante (mantido fixo) (Qc);
Tempo final de simulação (t_final);
Passo do método iterativo (H);
Vazão volumétrica da corrente de alimentação de reagentes (qr)

