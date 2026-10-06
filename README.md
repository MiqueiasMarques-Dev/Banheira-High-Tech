# Banheira-High-Tech
class Banheira():
    def __init__(self):
        self.__temperatura = 0
        self.__estado = False
        self.__usuario = ""
        self.__senha = ""
        self.__idade = 0
    
    @property
    def temperatura(self):
        return self.__temperatura

    @temperatura.setter
    def temperatura(self, a):
        self.__temperatura = a

    @property 
    def estado(self):
        return self.__estado

    @estado.setter
    def estado(self, a):
        self.__estado = a
    
    @property
    def usuario(self):
        return self.__usuario
    
    @usuario.setter
    def usuario(self, a):
        self.__usuario = a

    @property
    def senha(self):
        return self.__senha

    @estado.setter
    def senha(self, a):
        self.__senha = a

    @property
    def idade(self):
        return self.__idade

    @idade.setter
    def idade(self, a):
        self.__idade = a

    def exibir_temperatura(self):
        print(self.temperatura)

    def emitir_som(self):
        """bipar"""
    
    def 
    ###receber exibir histórico som led ligardesligar logar
