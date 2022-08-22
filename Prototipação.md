# `Prototipagem do app Save Money`

## 1 Introdução
Contruir um protótipo de um produto seja ele digital ou material é um método crucial 
para se obter feedback sobre todas as funcionalidades e interfaces do produto. Ele permite que as partes envolvidas façam experiências com o modelo desenvolvido. 

## 2 Funcionalidades
- Cadastro de Perfil
- login
- logout
- Criar lista
- Pesquisar produto
- Alterar perfil
- Comparamento de preços

## 3 React Native
Como atualmente o framework React Native é um dos mais populares no desenvolvimento Mobile. Fora o seu bom desenpenho em comparação a outros meios de implementação
mobile, nós escolhemos ele para darmos inicio ao desenvolvimento. Seu recurso de aproveitamento de código e a possibilidade de podemos implementar um código que rode 
nas duas principais plataformas do mercado(android e iOS). Facilitará no ganho de produção.
Exemplo de código em React native:
~~~javascript
import { View, SafeAreaView, StyleSheet} from 'react-native';

import { StatusBar } from 'expo-status-bar';

import Form from '../components/Form';

import Header from '../components/Header';




export default function Home() {
  return (
    <SafeAreaView>
      <StatusBar style='dark' />
      <View style={styles.container}>
        <View >
            <Header />
        </View>
        <View>
          <Form />
        </View>
        
      </View>
      
    </SafeAreaView>
  );
};

const styles = StyleSheet.create({
  container: {
    backgroundColor: '#121212',
    height: '100%',
    marginTop: '6%'
  }
});

~~~

## Testes
Hoje criar uma aplicação Mobile seja para qual for a plataforma é crucial garantir a qualidade deste. Pois cada vez mais o uso de smartphones vêm crescendo no mundo interiro e fazer aplicações que garantam que irá funcionar de maneira perfeita nas mais diversas situações é fundamental. Com isso é fundamental criar bons testes para garantir o bom funcionamento das funcionalidades. Alguns dos testes a serem utilizado são:
- TDD (Test Driven Development)
- E2E (END-TWO-END)

## 3 Protótipo
### 3.1 Visão geral das telas
![Captura de Tela (82)](https://user-images.githubusercontent.com/98723501/185830605-e72cc732-197f-4c0d-8696-7d173aea92b1.png)

![Captura de Tela (81)](https://user-images.githubusercontent.com/98723501/185830220-cc0afd6b-ee63-48b4-8769-291d61829e46.png)

