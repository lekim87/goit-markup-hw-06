 <p class="modal-title">Заголовок модального окна</p>
        <form class="modal-form">
          <div class="form-field">
            <label for="user-name" class="modal-label">Введите имя*</label>
            <input
              type="text"
              name="user-name"
              class="modal-input"
              placeholder="John Dou"
              required
              id="user-name"
            />
          </div>
          <div class="form-field">
            <label for="user-email" class="modal-label">Введите почту</label>
            <input
              type="email"
              name="user-email"
              class="modal-input"
              placeholder="test@mail"
              required
              id="user-email"
            />
          </div>

          <div class="form-field">
            <label for="user-tel" class="modal-label">Введите телефон*</label>
            <input
              type="tel"
              name="user-tel"
              class="modal-input"
              placeholder="+380"
              required
              id="user-tel"
            />
          </div>
          <div class="form-field">
            <label for="user-text" class="modal-label">Коментарий</label>
            <textarea
              name="user-text"
              id="user-text"
              class="modal-text"
              placeholder="коммент"
            ></textarea>
          </div>
          <fieldset>
            <legend>Size</legend>
            <label for="big-size">40sm</label>
            <input type="radio" name="size" id="big-size" value="big-size" />
            <label for="small-size">30sm</label>
            <input
              type="radio"
              name="size"
              id="small-size"
              value="small-size"
            />
          </fieldset>
          <fieldset>
            <legend>add</legend>
            <label for="cheese">cheese</label>
            <input
              type="checkbox"
              checked
              name="add"
              id="cheese"
              value="cheese"
            />
            <label for="peperoni">peperoni</label>
            <input type="checkbox" name="add" id="peperoni" value="peperoni" />
          </fieldset>
          <div class="form-field">
            <label for="city">City</label>
            <select name="pizza-city" id="city" class="modal-input">
              <option value="London"></option>
              <option value="Paris">Paris</option>
              <option value="Novyy Rozdil">Novyy Rozdil</option>
            </select>
          </div>
          <button type="submit">Submit</button>
          <button type="reset">Reset</button>
        </form>
