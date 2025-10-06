import rando

def coin_toss():
    return "Heads" if random.choice([True, False]) else "Tails"

if __name__ == "__main__":
    print(f"Coin toss result: {coin_toss()}")
