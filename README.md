# thesis

# additional resources
- [Terms: Independent and Identically Distributed (IID)](https://www.youtube.com/watch?v=EGKbPww2_rc)
---
## Federated Learning: Collaborative Machine Learning
---

Federated learning aims to train a single model from multiple data sources, under the constraint that data stays at the source and is not exchanged by the data sources (a.k.a. nodes, clients, or workers) nor by the central server orchestrating training, if present.

![image](https://user-images.githubusercontent.com/59027621/180593187-3ab0ef9f-39f8-40fd-a810-282c20418873.png)

In a typical federated learning scheme, a central server sends model parameters to a population of nodes (also known as clients or workers). The nodes train the initial model for some number of updates on local data and send the newly trained weights back to the central server, which averages the new model parameters (often with respect to the amount of training performed on each node). In this scenario the data at any one node is never directly seen by the central server or the other nodes, and additional techniques, such as secure aggregation, can further enhance privacy.

Imagine having access to text messages, emails, WhatsApp chats, Facebook and LinkedIn messages from millions of distinct accounts across the world in a bid to build a keypad next-word predictor. Or having an unrestricted access to billions of medical records across continents while predicting the chance of diabetes in a patient. These hypothetical scenarios underscore what data quantity and quality means in machine learning, but they are nowhere near being realisable in today’s world. Thanks to the tough data protection laws now in place nearly worldwide.

### Federated Learning (FL) to the rescue

![image](https://user-images.githubusercontent.com/59027621/180593638-9063af30-4204-4934-9196-2b1e3e4d102a.png)

Just as the image on the left, quality data exist like islands across edge devices around the world. But harnessing them into one piece to leverage their predictive power without contravening privacy laws is a herculean task. This challenge is what necessitated the FL technology. FL provides a clever way to connect machine learning models to the data required to effectively train them. So how does FL achieve this without breaching data protection laws? Read on as I take you through one of the hottest subjects in machine learning (ML) today.
