# audit AichiINU
ADDITIONAL INFORMATION FOLLOWING THE AUDIT OF AICHIINU TOKEN
SmartContract
AichiINU® is an encrypted messaging platform that keeps the privacy of its users safe by proposing a strong and efficient alternative to emails.

With AichiINU, no more SPAM, scammer mails, phishing mails, spyware and other malware, and no more data transfer and storage duration limit!

Messages and documents are encrypted before being sent to AichiINU. They are then stored in a decentralized SafePost database accessible in high availability.

AichiINU uses open source libraries to encrypt and decrypt messages and documents: this gives the guarantee that algorithms used have no back door.

No ads, no statistics. Messages and documents remain confidential: NO THIRD PARTY, including the SafePost team, can neither decrypt nor read them!

AichiINU proposes an ERC20 token whose name is AichiINU.
“AichiINU” TOKEN AUDIT
TOKEN STRUCTURE
Name : AichiINU
Symbol: AichiINU
Decimal: 9
Total supply: 100,000,000,000
Smart contract address: 0x8B826d3cA8Fcd72075820816cD649232C8CFdDB8
The code of our smart contract is available at the following URL: https://bscscan.com/token/0x8B826d3cA8Fcd72075820816cD649232C8CFdDB8
The audit of “AichiINU”-token performed by Kiwifinanceswap
ADDITIONAL INFORMATION FOLLOWING THE AUDIT OF Kiwifinanceswap
To avoid double withdrawal attack we created a user interface in such a way that we set the allowance first to 0 before setting it to another value for the same spender. Line 105 of our contract checks this condition.
To avoid the problem of ERC20 lack of transaction handling mechanism we added check of the receiver address at line 47.


