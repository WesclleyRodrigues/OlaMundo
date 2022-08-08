
namespace Curso_cs
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Olá Mundo!");
            Console.WriteLine("Começando a programar...");
            Console.ReadLine();



namespace CalculaMedia
{
    internal class Program
    {
        static void Main(string[] args)
        {
            /*Mine levantameto de requisitos
             * saber quem é o aluno
             * notas do aluno
             * calcular a media 
             * mostrar o calculo para o usuario
             */

            string nomeAluno;
            float nota1, nota2, nota3, nota4, media;

            //Solicitar a entrada de dados pelo usuario

            Console.Write("Informe o nome do aluno(a): ");
            nomeAluno = Console.ReadLine();
            Console.Write("Informe a nota1: ");
            nota1 = Convert.ToSingle ( Console.ReadLine());
            Console.Write("Informe a nota2: ");
            nota2 = Convert.ToSingle(Console.ReadLine());
            Console.Write("Informe a nota3: ");
            nota3 = Convert.ToSingle(Console.ReadLine());
            Console.Write("Informe a nota4: ");
            nota4 = Convert.ToSingle(Console.ReadLine());

            //CALCULAR A MÉDIA
            media = (nota1 + nota2 + nota3 + nota4) / 4;
            //
            //MOSTRAR MÉDIA
            Console.WriteLine("A média do aluno(a) {0} é {1}", nomeAluno, media);

            Console.ReadKey();


        }
    }
}
