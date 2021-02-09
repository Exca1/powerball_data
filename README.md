# powerball_data

-- Pulls data from the Lottery Database--

SELECT 
substr(WinningNumbers,1,2) as Number_01, 
substr(WinningNumbers,4,2) as Number_02,
substr(WinningNumbers,7,2) as Number_03,
substr(WinningNumbers,10,2) as Number_04,
substr(WinningNumbers,13,2) as Number_05,
substr(WinningNumbers,16,2) as Number_06
From Lottery_Powerball_Winning_Numbers__Beginning_2010;

