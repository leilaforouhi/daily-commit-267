def get_shortest_word(sentence):
    words = sentence.split()

    if not words:
        return ""

    return min(words, key=len)


if __name__ == "__main__":
    text = "Python makes daily coding enjoyable"

    print("Sentence:", text)
    print("Shortest word:", get_shortest_word(text))
