# sg-pupil-attainment-em
Number of pupils in Edinburgh who attained gained awards in English and Maths at SCQF Level 3 or above.

Statistics provided by Scottish Government:  http://statistics.gov.scot/data/pupil-attainment-em

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/sg-pupil-attainment-em.git
```

Install npm dependencies

```
cd sg-pupil-attainment-em
npm install
```

Run the API (from the sg-pupil-attainment-em directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
