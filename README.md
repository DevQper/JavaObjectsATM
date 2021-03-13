# JavaObjectsATM
create table accounts (
AccountNumber int primary key,
Pin int, 
AvailiableBalance real,
TotalBalance real
)

INSERT INTO accounts(AccountNumber, Pin, AvailiableBalance, TotalBalance)
VALUES (12345, 54321, 1000.0, 1200.0),
(67890, 09876, 200.0, 200.0),
(22222, 11111, 0.0, 0.0)
RETURNING *;
