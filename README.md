# Miskatonic-universit
#include <iostream>
#include <string>
#include <algorithm>

int main() {

std::string s = "E.D.W.A.R.D N.I.G.M.A!";
auto it = std::remove(s.begin(), s.end(), '.');
s.erase(it, s.end());
std::cout << s << std::endl;
return 0;
}
