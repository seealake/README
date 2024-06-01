def round(number):
    # 将banking rounding改成四舍五入
    if number > 0:
        return int(number + 0.5)
    else:
        return int(number - 0.5)
