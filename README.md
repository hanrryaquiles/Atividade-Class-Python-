# Atividade-Class-Python-# Definição da classe
class Carro:
    # atributos
    marca = "Fiat"
    ano = 2020

    # métodos
    def mostrar_info(self):
        print("Marca:", self.marca)
        print("Ano:", self.ano)

    def ligar(self):
        print("O carro está ligado!")

# Criando um objeto
meu_carro = Carro()

# Exibindo os atributos
print("Atributos do objeto:")
print(meu_carro.marca)
print(meu_carro.ano)

# Chamando os métodos
meu_carro.mostrar_info()
meu_carro.ligar()
