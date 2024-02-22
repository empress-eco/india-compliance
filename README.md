<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">


India Compliance is a tool designed to simplify compliance with Indian business regulations, making it a must-have for any operation in India. It integrates with GST APIs to streamline regular compliance processes, providing a seamless experience for users.

<div align="center">
    <a href="https://docs.indiacompliance.app/"><strong>Explore the Docs »</strong></a>
    <br />
    <a href="https://github.com/empress-eco/india-compliance/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/india-compliance/issues">Request Feature</a>
</div>

</div>

## Key Features
- End-to-end GST e-Waybill management.
- Automated GST e-Invoice generation and cancellation.
- Advanced purchase reconciliation based on GSTR-2B and GSTR-2A.
- Autofill Party and Address details by entering their GSTIN.
- Configurable features based on specific business needs.
- Powerful validations to ensure correct compliance.

## Technical Stack and Setup Instructions
India Compliance builds on top of the Framework and Empress. Ensure you have a Empress site set up before installing India Compliance.

**Installation**

Clone the repository using the following command:

```sh
git clone https://github.com/empress-eco/india-compliance.git
```

Then, navigate to your newly cloned directory and install the application on your site using the following commands:

```sh
# Download the app using the Bench CLI.
bench get-app --branch [branch name] 

# Install the app on your site.
bench --site [site name] install-app india_compliance
```
Replace `[branch name]` with the branch that you're using for Framework and Empress.

## Usage
Some automation features of India Compliance require access to [GST APIs](https://discuss.Empress.com/t/introducing-india-compliance/86335#a-note-on-gst-apis-3). Sign up for an India Compliance Account after installing the app to unlock these features.

## Contribution Guidelines
Contributions to India Compliance are always welcome. To contribute:

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License and Acknowledgements
**License**

This project is licensed under the MIT License. All your contributions will also be licensed under the MIT License.

**Acknowledgements**

We would like to express our gratitude to the Empress Community. Their innovative and dedicated work on foundational FOSS projects has been instrumental in the creation and continued development of India Compliance. We deeply appreciate their ongoing support and contributions.
