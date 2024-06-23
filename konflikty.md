konflikt danych (data hazard)
- niedostępność operandu, będącego wynikiem instrukcji nieukończonej
konflikt strukturalny (zasobu) (resource hasard)
- kilka instrukcji wymaga jednocześnie dostępu do unikatowego zasobu
- instrukcja wymaga kilka etapów EX
konflikt sterowania (control hazard)
- wznowienie potoku po pobraniu instrukcji docelowej (branch target)
- opóźnienie użycia warunku
	- rozgałęzienie warunkowe niewykonane 
		- instrukcja jest dekodowana dopiero w następnym cyklu po warunku
	- rozgałęzienie warunkowe wykonane
		- dekodowanie jest dopiero możliwe po pobraniu i wytworzeniu warunku
	- rozgałęzienie bezwarunkowe
		- dekodowanie dopiero możliwe po pobraniu