#ifndef ITEM_TO_PURCHASE_H
#define ITEM_TO_PURCHASE_H

#include <string>

class ItemToPurchase {
public:
    // Default constructor
    ItemToPurchase();

    // Mutator and accessor functions
    void SetName(const std::string& name);
    std::string GetName() const;

    void SetPrice(int price);
    int GetPrice() const;

    void SetQuantity(int quantity);
    int GetQuantity() const;

private:
    // Private data members
    std::string itemName;
    int itemPrice;
    int itemQuantity;
};

#endif // ITEM_TO_PURCHASE_H
