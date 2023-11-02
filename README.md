# graph_theory_neural_network

Projeto para a matéria de teoria de grafos. Projeto esse visando a estruturação de matriz de adjacencia e lista de adjacencia para cada rede neural estruturada. 

Para isso foram utilizados tanto os dicionários gerados pelo próprio keras sobre informações da estrutura de cada rede neural, assim como visualizações lógicas complemetnares. Exemplo dessa complementação foi a generalização de um layer anterior ao primeiro layer explicitado pelo dicionário retornado atráves do keras; layer esse para representar os inputs. Considerando que uma rede neural se adequa como um grafo ponderado, os valores de cada neuron foram definidos (a partir também do dicionário retornado pelo keras) de acordo com a seguinte equação: valor_neuron = peso_definido_para_neuron * input. Sendo "peso_definido_para_neuron" uma constante (após finalização do treinamento) e "input" valores variáveis de acordo com o input definido em determinado momento. Além disso, para facilitar a identificação dos neurons, o grafo gerado foi rotulado. 

Fundamentando esse projeto e permitindo a generalização para qualquer estrutura de rede neural gerada utilizando keras, foi utilizada programação orientada a objeto. Cada objeto é instanciado a partir de uma estrutura de rede neural, permitindo manipulação das informações da mesma de acordo com os requisitos do projeto.


Project for the subject of Graph Theory, aiming to structure adjacency matrices and adjacency lists for each structured neural network.

For this purpose, both the dictionaries generated by Keras itself on the network's structure information were used, as well as complementary logical visualizations. An example of this complement was the generalization of a layer preceding the first layer explicitly defined by the dictionary returned by Keras; this layer represents the inputs. Considering that a neural network can be treated as a weighted graph, the values of each neuron were defined (based on the dictionary returned by Keras as well) according to the following equation: neuron_value = defined_weight_for_neuron * input. "Defined_weight_for_neuron" is a constant (after the completion of training), and "input" takes variable values according to the input defined at a given moment. Furthermore, to facilitate the identification of neurons, the generated graph was labeled.

To underpin this project and enable generalization to any neural network structure generated using Keras, object-oriented programming was used. Each object is instantiated based on a neural network structure, allowing for manipulation of its information according to the project's requirements.
