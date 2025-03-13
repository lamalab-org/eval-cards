# Evaluation Cards for Machine Learning in Materials Science

This repository contains templates and examples for creating evaluation cards - structured documents for describing and documenting machine learning evaluation frameworks in materials science.

You can upload evaluation cards in [a HuggingFace Space](https://huggingface.co/spaces/jablonkagroup/eval-cards-gallery).

## What are Evaluation Cards?

Evaluation cards are structured documents that capture key aspects of ML evaluation frameworks through the lens of measurement theory. They promote transparency about design choices, limitations, and tradeoffs in evaluation frameworks. Inspired by model cards and data cards, evaluation cards help developers document and users understand:

- What is being measured (estimand)
- How it is measured (estimator)
- How results should be reported (estimate)

## Getting Started

1. Start with the [template](./template.md) in this repository
2. Review the examples:
    - [ChemBench](https://github.com/lamalab-org/chembench/blob/dev/eval-card.md)
    - [MaCBench](https://github.com/lamalab-org/macbench/blob/main/eval-card.md)


## Template Structure

The template is organized around three core concepts:

- **Estimand**: What you want to measure
- **Estimator**: How you measure it
- **Estimate**: How results should be reported

Key sections include:
- Evaluation Design
- Target Constructs
- Assessment Components
- Metrics and Protocols
- Known Limitations
- Usage Guidelines


## Contributing

We welcome contributions! Please see our [contribution guidelines](CONTRIBUTING.md) for details on:
- Adding new examples
- Improving the template
- Reporting issues

### Pull Request Process

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request with a clear description


## Citation

If you use this template in your work, please cite:
```bibtex
[Citation to be added after publication]
```

## Related Work

- [Model Cards for Model Reporting (Mitchell et al.)](https://arxiv.org/abs/1810.03993)
- [Data Cards (Pushkarna et al.)](https://arxiv.org/abs/2204.01075)
- [Datasheets for Datasets (Gebru et al.)](https://arxiv.org/abs/1803.09010)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

