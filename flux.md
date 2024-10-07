flowchart TD
 subgraph s1["Untitled subgraph"]
        n1["Untitled Node"]
  end
    A["Début"] --> B["Accéder à la liste des véhicules disponibles"]
    B --> C["Filtrer les véhicules selon les critères"]
    C --> D["Afficher la liste des véhicules filtrés"]
    D --> E["Sélectionner un véhicule"]
    E --> F["Choisir la durée de location"]
    F --> G["Sélectionner des options supplémentaires"]
    G --> H["Créer une réservation"]
    H --> I["Accéder à l'interface de paiement"]
    I --> J["Entrer les informations de paiement"]
    J --> K["Confirmer le paiement"]
    K --> L{"Le paiement est-il réussi ?"}
    L -- Oui --> M["Confirmer la réservation"]
    L -- Non --> N["Afficher une erreur de paiement"]
    M --> O["Accéder à l'espace administrateur"] & T["Fin"]
    O --> P["Gérer la flotte de véhicules"] & Q["Gérer les réservations"] & R["Accéder aux informations clients"] & S["Générer des rapports"]
    N --> T
    P --> T
    Q --> T
    R --> T
    S --> T



