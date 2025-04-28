# Legal Ontology for Indian Court Judgments

This repository hosts the **Legal Ontology for Indian Court Judgments**, a structured representation of key legal entities and their relationships. The ontology models roles like Petitioner, Respondent, Judge, Lawyer, Witness, and Other Persons, alongside legal artifacts such as Statutes, Provisions, Precedents, Courts, and Organizations.

The ontology is designed using OWL 2 standards and saved in RDF syntax for compatibility with popular visualization tools like WebVOWL.

---

## 📚 Ontology Details

- **Ontology IRI:** `https://github.com/AjayMukundS/LegalOntology`
- **Version IRI:** `https://github.com/AjayMukundS/LegalOntology/1.6.6`
- **Version:** v1.6.6
- **Creator:** Ajay Mukund S and Dr. K. S. Easwarakumar - Department of Computer Science and Engineering, College of Engineering Guindy, Anna University
- **Description:** A comprehensive ontology capturing entities and relationships prevalent in Indian court judgments for use in legal NLP, knowledge graphs, and AI applications.
- **Language:** English
- **License:** [MIT LICENSE]

---

## 🛠 Features

- 14 Core Legal Entity Classes:
  - Petitioner, Respondent, Judge, Lawyer, Witness, Other Person
  - Statute, Provision, Precedent
  - Court, Organization (ORG), Geopolitical Entity (GPE)
  - Case Number, Date

- Exhaustive Object Properties Modeling:
  - Relationships like `hasPetitioner`, `hasRespondent`, `judgedBy`, `citesPrecedent`, etc.
  - Domain and Range constraints accurately set.
  - Disjointness, hierarchy, and semantic annotations incorporated.

- Metadata Annotations:
  - Title, Creator, Description, Version, Publisher, Date.

- Fully compatible with:
  - [WebVOWL](https://vowl.visualdataweb.org/webvowl.html) for interactive visualization.
  - OWL Reasoners for semantic inference.

---

## 📈 Visualization

You can explore the ontology interactively via WebVOWL here:

🔗 **[Visualize Ontology in WebVOWL](#)**

*(Link will be updated once GitHub Pages is configured.)*

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the `.owl` or `.rdf` file in [Protégé](https://protege.stanford.edu/) for local editing.
3. Upload the ontology file to [WebVOWL](https://vowl.visualdataweb.org/webvowl.html) to view and explore.

---

## ⚖️ License

This ontology is licensed under the **MIT License**.  
You are free to share, adapt, and build upon the ontology for any purpose, even commercially, provided that proper attribution is given.

For license details, see [LICENSE](LICENSE) file.

---

## 🤝 Contributions

Contributions, feedback, and suggestions are welcome!  
Feel free to open an issue or submit a pull request.

---

## 📧 Contact

For inquiries, please contact: [ajaymukund1998@gmail.com, easwara@annauniv.edu]
