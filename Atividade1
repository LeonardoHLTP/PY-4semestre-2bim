class Curso:
    def __init__(self, nome, duracao):
        self.nome = nome
        self.duracao = duracao

    def detalhes_do_curso(self):
        return f"Nome do curso: {self.nome}\nDuração do curso: {self.duracao} anos"


class Presencial(Curso):
    def __init__(self, nome, duracao, numero_de_vagas):
        super().__init__(nome, duracao)
        self.numero_de_vagas = numero_de_vagas

    def detalhes_do_curso(self):
        return f"{super().detalhes_do_curso()}\nNúmero de vagas presenciais: {self.numero_de_vagas}"


class Online(Curso):
    def __init__(self, nome, duracao, plataforma_online):
        super().__init__(nome, duracao)
        self.plataforma_online = plataforma_online

    def detalhes_do_curso(self):
        return f"{super().detalhes_do_curso()}\nPlataforma online: {self.plataforma_online}"

curso_presencial = Presencial("Curso Presencial", 2, 50)
curso_online = Online("Curso Online", 3, "Plataforma Virtual")

print("Detalhes do Curso Presencial:")
print(curso_presencial.detalhes_do_curso())
print("\nDetalhes do Curso Online:")
print(curso_online.detalhes_do_curso())
