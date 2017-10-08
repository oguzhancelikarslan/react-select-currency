# react-select-currency
Select a currency from a drop-down list of countries with auto-fill.

# Usage

On command line:
        
        (npm | yarn) react-select-currency

In your JSX code
        import React from 'react';
        import SelectCurrency from '../src'


        const onSelectedCurrency = currencyAbbrev => {
            debug(`Selected ${currencyAbbrev}`)
        }

        function Demo() {
            return (
                <div>
                    <SelectCurrency value={'USD'} onCurrencySelected={onSelectedCurrency} />
                </div>
            )
        }

# Credits
This component makes use of the following components, with thanks and acknowledgement to the authors and contributors:

* [country-code](https://github.com/ckaatz-nokia/cc)
* [flag-icon-css](https://github.com/lipis/flag-icon-css)
* [locale-currency](https://github.com/tadeegan/locale-currency)

# Author
Lawrence Siden  
Ann Arbor, MI

# License
[MIT](https://opensource.org/licenses/MIT)
