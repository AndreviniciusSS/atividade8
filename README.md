- Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule e mostre o total do seu salário no referido mês.

import java.util.Scanner;
import javax.swing.JOptionPane;

class Main {
  public static void main(String[] args) {
Scanner console = new Scanner(System.in);

    Double valorHora;
        Double horasTrabalhadas;
        Double valorMes;
 
        System.out.println("Informe o valor que você ganha a hora");
        valorHora = Double.parseDouble(JOptionPane.showInputDialog("Informe o valor que você ganha a hora"));
 
        System.out.println("Informe as horas trabalhadas no mês");
        horasTrabalhadas = Double.parseDouble(JOptionPane.showInputDialog("Informe as horas trabalhadas no mês"));
 
        valorMes = (valorHora * horasTrabalhadas);
 
        System.out.println("O valor do salário no mês é de " + valorMes);
