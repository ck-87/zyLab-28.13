#include "ItemToPurchase.h"

// Default constructor
ItemToPurchase::ItemToPurchase()
    : itemName("none"), itemPrice(0), itemQuantity(0) {}

// Mutator and accessor functions
void ItemToPurchase::SetName(const std::string& name) {
    itemName = name;
}

std::string ItemToPurchase::GetName() const {
    return itemName;
}

void ItemToPurchase::SetPrice(int price) {
    itemPrice = price;
}

int ItemToPurchase::GetPrice() const {
    return itemPrice;
}

void ItemToPurchase::SetQuantity(int quantity) {
    itemQuantity = quantity;
}

int ItemToPurchase::GetQuantity() const {
    return itemQuantity;
}
