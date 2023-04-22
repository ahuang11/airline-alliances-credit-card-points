# airline-alliances-credit-card-points

CSV file that shows the airline alliances and the banks that allow transfer of points/miles to the airlines' loyalty programs.

To use:
```python
import pandas as pd

url = "https://raw.githubusercontent.com/ahuang11/airline-alliances-credit-card-points/main/airline_alliances_credit_card_points.csv"
df = pd.read_csv(url)
print(df)
```

The CSV file includes the following columns:

`Alliance`: The name of the airline alliance to which the airlines belongs. If it does not belong to any alliance, the name of the airline is used.
`Airline`: The names of the airlines within the alliance.
`Bank`: The name of the bank that allows the transfer of points/miles to the airline's loyalty program.

**Please note that the CSV file may become outdated, so use it at your own risk.**

If you spot any errors or updates that need to be made, please file an issue.