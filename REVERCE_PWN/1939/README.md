# medium
Вы получили программу, которая переводит любую последовательность символов в новую, посредством замены символов на входной ленте и переключения режимов работы.

    assert tape.startswith('mctf{')
    assert tape[-1] == '}'
    tape = list(tape)
    position = 0
    state = 1
    while state != 0:
        letter, move, state = table[(state, tape[position])]
        tape[position] = letter
        if move == 'L': position -= 1
        elif move == 'R': position += 1
    result = ''.join(tape)
    print(result)
    # 8qxe78ui}2kcvn3kjg7km2tl7hc0o{xs
К слову этот кусок кода не есть программа выполняющая замену символов
