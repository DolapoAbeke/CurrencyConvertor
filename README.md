# CurrencyConvertor
int main() {
  //declaring currency
  double pesos;
  double reais;
  double soles;

  double dollars;

    std::cout << "Enter numbers of Colombian Pesos \n";
  std::cin >> pesos;

    std::cout << "Enter numbers of Colombian reais \n";
  std::cin >> reais;

    std::cout << "Enter numbers of Colombian soles \n";
  std::cin >> soles;

// Pesos conversion rate: 0.061
// Reais conversion rate: 0.20 
// Soles conversion rate: 0.27

double conversion_rate1 = 0.061;

double conversion_rate2 = 0.20 ;

double conversion_rate3 =  0.27;


dollars = 
(conversion_rate1*pesos)+
(conversion_rate2*reais)+
(conversion_rate3*soles);

std::cout << "US dollar is " << dollars << "\n";

  return 0;
