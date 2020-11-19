Use Cloudrail in your Terraform CircleCI pipelines, to look for security vulnerabilities in your Terraform code.

[What are Orbs?](https://circleci.com/orbs/)

## Usage

### Setup

In order to use the Indeni Cloudrail Orb on CircleCI you will need to first register a Cloudrail account (if you haven't already) and get your Cloudrail API key. In addition, Cloudrail operates on a Terrform plan file. Your pipeline needs to create the plan first (with ```-out=filename```), and pass the file to the Cloudrail orb.

### Use In Config

For full usage guidelines, see the [orb registry listing](http://circleci.com/orbs/registry/orb/indeni/cloudrail).

---

## Contributing

We welcome [issues](https://github.com/indeni/cloudrail-circleci-orb/issues) to and [pull requests](https://github.com/indeni/cloudrail-circleci-orb/pulls) against this repository!
