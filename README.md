# Homework_module20

## 1. Joint Savings Account in Solidity
- Upload and open `joint_savings.sol` in Remix.
- Create:
  - Contract: `JointSavings`.
  - Variables: `accountOne`, `accountTwo`, `lastToWithdraw`, `lastWithdrawAmount`, `contractBalance`.
  - Functions: `withdraw`, `deposit`, `setAccounts`.
  - Fallback function.

## 2. Compile & Deploy

## 3. Interact with Contract
- Set accounts:
  - ![setAccounts](Execution_Results/setAccounts.png)
- Test deposits:
  - 1 ether in wei ![deposit 1 ether in wei](Execution_Results/Send 1 ether as wei.png)
  - 10 ether in wei ![deposit 10 ether in wei](Execution_Results/Send 10 ether as wei.png)
  - 5 ether ![deposit 5 ether](Execution_Results/Send 5 ether.png)
- Test withdrawals:
  - 5 ether to accountOne.
    ![5 ether to accountOne](Execution_Results/5 ether into accountOne.png)
    ![transaction1](Execution_Results/balance after transaction1.png)
  - 10 ether to accountTwo.
    ![10 ether to accountTwo](Execution_Results/10 ether into accountTwo.png)
    ![transaction2](Execution_Results/balance after transaction2.png)
