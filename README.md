# JSON Examples Repository

This repository contains a collection of example JSON files for testing, benchmarking, and demonstrating JSON parsing libraries and tools. The examples include various types of JSON structures, from simple objects to complex nested data, and cover different use cases such as API responses, configuration files, and data exports.

## Contents

### jsonexamples Directory

- **jsonexamples/apache_builds.json**: JSON data related to Apache build configurations
- **jsonexamples/canada.json**: Geographic data for Canada (likely GeoJSON format)
- **jsonexamples/citm_catalog.json**: CITM (Computer Information Technology and Management) catalog data
- **jsonexamples/github_events.json**: Sample GitHub API events data
- **jsonexamples/google_maps_api_compact_response.json**: Compact version of Google Maps API response
- **jsonexamples/google_maps_api_response.json**: Full Google Maps API response example
- **jsonexamples/gsoc-2018.json**: Google Summer of Code 2018 data
- **jsonexamples/instruments.json**: Financial instruments data
- **jsonexamples/marine_ik.json**: Marine inverse kinematics data
- **jsonexamples/mesh.json**: 3D mesh data
- **jsonexamples/mesh.pretty.json**: Pretty-printed version of mesh data
- **jsonexamples/numbers.json**: Collection of numeric data examples
- **jsonexamples/random.json**: Randomly generated JSON data
- **jsonexamples/repeat.json**: JSON with repeated structures
- **jsonexamples/semanticscholar-corpus.json**: Academic corpus data from Semantic Scholar
- **jsonexamples/tree-pretty.json**: Pretty-printed tree structure data
- **jsonexamples/twitter_api_compact_response.json**: Compact Twitter API response
- **jsonexamples/twitter_api_response.json**: Full Twitter API response example
- **jsonexamples/twitter_timeline.json**: Twitter timeline data
- **jsonexamples/twitter.json**: General Twitter data
- **jsonexamples/twitterescaped.json**: Twitter data with escaped characters
- **jsonexamples/update-center.json**: Software update center configuration

## ndjson

- **jsonexamples/amazon_cellphones.ndjson**: Newline-delimited JSON file containing Amazon cell phone data

### jsonchecker Directory

Contains JSON files for testing JSON parsing, including valid and invalid examples:

- Various fail*.json files for invalid JSON
- pass*.json files for valid JSON

### adversarial Directory

Contains adversarial JSON examples designed to test parser robustness:

- **adversarial/issue150/**: Specific test cases

### minefield Directory

Additional test cases for JSON parsing edge cases.

## Usage

These JSON files can be used for:

- Testing JSON parsing libraries and tools
- Benchmarking JSON processing performance
- Learning JSON structures and formats
- Developing and validating JSON-related software
- Educational purposes

## Contributing

Feel free to contribute additional JSON examples by submitting pull requests. Please ensure that:

- Files are valid JSON
- File names are descriptive
- Examples represent real-world use cases where possible
- Sensitive or personal data is not included

## Citation

If you use this dataset in research or a publication, please cite it.


Example BibTeX entry:

```bibtex
@misc{simdjson-data,
  title = {{simdjson-data: A collection of JSON example files}},
  author = {Daniel Lemire},
  year = {2025},
  howpublished = {\url{https://github.com/simdjson/simdjson-data}}
}
```


## License

This repository is provided for educational and testing purposes. Please check individual files for any specific licensing information.
