# Codex-fantasy
To help create codes for developmental work
#include <iostream>
using namespace std;

class BankAccount {
private:
    double balance;  // Hidden from outside the class

    public:
        BankAccount(double initialBalance) {
                balance = initialBalance;
                    }

                        void deposit(double amount) {
                                if (amount > 0) {
                                            balance += amount;
                                                    }
                                                        }

                                                            double getBalance() {
                                                                    return balance;
                                                                        }
                                                                        };

                                                                        int main() {
                                                                            BankAccount account(1000)
                                                                         account.deposit(700)
                                                                                

                                                                                    cout << "Account balance: ₹" << account.getBalance() << endl;

                                                                                        return 0;
                                                                                        }