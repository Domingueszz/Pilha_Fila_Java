```mermaid
    classDiagram
    class Pilha {
        + push(elemento: Object): void
        + pop(): Object
        + peek(): Object
        + isEmpty(): boolean
    }
    
    class Fila {
        + enqueue(elemento: Object): void
        + dequeue(): Object
        + peek(): Object
        + isEmpty(): boolean
    }

    Pilha --|> Object
    Fila --|> Object
