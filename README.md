# Logistics Shipping Rate

![Python 3](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue)

A small command-line **shipping cost calculator** written in Python. Enter a package's weight and the rate per kilogram, and it prints the shipping cost.

## How it works

```
shipping cost = weight (kg) × rate per kg
```

The script reads both values with `input()`, converts them to floats, multiplies them, and prints the result in USD. It uses only the Python standard library.

## Usage

Requires Python 3.6 or later.

```bash
git clone https://github.com/ShaileshXB/LogisticsShippingRate.git
cd LogisticsShippingRate
python3 Shipping_Cost_Calculator.py
```

## Example

```
$ python3 Shipping_Cost_Calculator.py
Enter the package weight in kilograms: 2.5
Enter the shipping rate per kilogram: 4
Shipping Cost: 10.0 USD
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) and the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

Licensed under the [Apache License 2.0](LICENSE).
